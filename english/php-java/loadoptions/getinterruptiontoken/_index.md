---
title: getInterruptionToken
type: docs
weight: 80
url: /php-java/loadoptions/getinterruptiontoken/
---

# getInterruptionToken() method

 The token to monitor for interruption requests.
 
 This token manages the whole  IPresentation instance lifetime. Any long-running operation, such as loading 
 or saving of presentation, will be interrupted via calling of the  InterruptionTokenSource#interrupt method of 
 the  InterruptionTokenSource.
 

##  Returns
InterruptionTokenSource

