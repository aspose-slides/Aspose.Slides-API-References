---
title: checkWriteProtection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 30
url: /php-java/presentationinfo/checkwriteprotection/
---

## checkWriteProtection(String password)  method

 Checks whether a password to modify is correct for a write protected presentation.
 

 
```php
  $info = PresentationFactory->getInstance()->getPresentationInfo($presentationFilePath);
  if ($info->isWriteProtected() == NullableBool::True) {
    $isWriteProtectedByPassword = $info->checkWriteProtection("my_password");
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| password | String | The password to check. 1. You should check the ( #isWriteProtected) property before calling this method. 2. When password is null or empty, this method returns false. |

### Returns
boolean

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | If a presentation is protected by a password to open or format does not support write protection |


---


