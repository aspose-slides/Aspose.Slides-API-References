---
title: setOnlyLoadDocumentProperties
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 260
url: /php-java/loadoptions/setonlyloaddocumentproperties/
---

## setOnlyLoadDocumentProperties(boolean value)  method

 This property makes sense, if presentation file is password protected.
 Value of true means that only document properties must be loaded from an encrypted 
 presentation file and password must be ignored.
 Value of false means that entire encrypted presentation must be loaded with use of right 
 password.
 If presentation isn't encrypted then property value is always ignored.
 If document properties of an encrypted file aren't public and property value is true then
 document properties cannot be loaded and exception will be thrown.
 Read/write  boolean.
 

### Returns
void


---


