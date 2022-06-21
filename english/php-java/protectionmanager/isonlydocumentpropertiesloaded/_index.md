---
title: isOnlyDocumentPropertiesLoaded
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 70
url: /php-java/protectionmanager/isonlydocumentpropertiesloaded/
---

## isOnlyDocumentPropertiesLoaded() method

 This property makes sense, if presentation file is password protected and document 
 properties of this file are public.
 Value of true means that only document properties are loaded from an encrypted 
 presentation file without use of password.
 Value of false means that entire encrypted presentation is loaded with use of right 
 password, not only document properties are loaded.
 If presentation isn't encrypted then property value is always false.
 If document properties of an encrypted file aren't public then property value is always false.
 If Presentation.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded 
 property value is always false.
 Read-only  boolean.
 

### Returns
boolean


---


