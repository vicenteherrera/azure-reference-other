---
title: "Error 0020 | Microsoft Docs"
titleSuffix: "Azure Machine Learning Studio"
ms.date: 07/19/2016
ms.service: "machine-learning"
ms.subservice: "studio"
ms.topic: "reference"

author: ericlicoding
ms.author: amlstudiodocs
manager: cgronlun
---
# Error 0020  
 Exception occurs if number of columns in some of the datasets passed to the module is too small.  
  
 You will receive this error in Azure Machine Learning if not enough columns have been selected to be used for a module.  
  
## Resolution  
 Revisit the module and ensure that column selector has correct number of columns selected.  
  
|Exception Messages|  
|------------------------|  
|Number of columns in input dataset is less than allowed minimum.|  
|Number of columns in input dataset is less than allowed minimum of {0} column(s).|  
|Number of columns in input dataset "{0}" is less than allowed minimum of {1} column(s).|  
  
 > [!TIP]
 >  Need more help or troubleshooting tips for Azure Machine Learning? Try these resources:  
 >  
 >  -  [Troubleshooting guide: Create and connect to an Machine Learning workspace](https://azure.microsoft.com/documentation/articles/machine-learning-troubleshooting-creating-ml-workspace/)  
 >  -  [Azure Machine Learning Frequently Asked Questions (FAQ)](https://azure.microsoft.com/documentation/articles/machine-learning/studio/faq/)  
  
## See also  
 [Module error codes](../machine-learning-module-error-codes.md)
