---
title: checkPassword
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/presentationinfo/checkpassword/
---

## checkPassword(String password)  method

 Checks whether a password is correct for a presentation protected with open password.
 

 
```php
  $info = PresentationFactory->getInstance()->getPresentationInfo($presentationFilePath);
  $isPasswordCorrect = $info->checkPassword("my_password");
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| password | String | The password to check. When the password is null or empty, this method returns false. |

### Returns
boolean

### Exception

| Exception | Condition |
| --- | --- |
 | NotSupportedException | if format is not supported to check passwords. |


---


