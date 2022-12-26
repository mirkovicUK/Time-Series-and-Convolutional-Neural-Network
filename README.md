TIME SERIES: 
Dataset: GunPoint
https://www.timeseriesclassification.com/description.php?Dataset=GunPoint

1. AR+MR+plot:
    * NonStatutoryDataGenerator
    * Data Cleaning
    * Auto regeresiv and Moving Average model implementation
    
2. TimeSeries_prediction_ComputerVision using GunPoint dataset
    * Encript TimesSeries using GramianAngularField, MarkovTransitionField, RecurrencePlot
      https://pyts.readthedocs.io/en/stable/generated/pyts.image.GramianAngularField.html
    * using FastAi higher level library written on top of PyTorh
    * foloving course Practical Deep Learning for coders: https://course.fast.ai/
    
3. PyTorch_only using GunPoint dataset
    * Aproach as above (2.) only this time using PyTorch library, folowing Intro to Deep Learning with PyTorch Udacity course
    https://www.udacity.com/course/deep-learning-pytorch--ud188
    * build, train and evaluate simple neural net for classification  
    * use prtrained arhitecture resnet18 and finetune it for this dataset , transfer learning
