---
title: checkWriteProtection
type: docs
weight: 20
url: /php-java/presentationinfo/checkwriteprotection/
---

# checkWriteProtection(java.lang.String) method

 Checks whether a password to modify is correct for a write protected presentation.
 

 
```php
  $info = PresentationFactory->getInstance()->getPresentationInfo($presentationFilePath);
  if ($info->isWriteProtected() == NullableBool::True) {
    $isWriteProtectedByPassword = $info->checkWriteProtection("my_password");
  }
```

##  Parameters

| name | description |
| --- | --- |
| password | The password to check. 1. You should check the ( #isWriteProtected) property before calling this method. 2. When password is null or empty, this method returns false. |

##  Returns
True if the presentation is write protected and the password is correct. False otherwise.

##  Exception
InvalidOperationException If a presentation is protected by a password to open or format does not support write protection


