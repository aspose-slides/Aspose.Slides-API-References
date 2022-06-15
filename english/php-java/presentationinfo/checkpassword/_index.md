---
title: checkPassword
type: docs
weight: 10
url: /php-java/presentationinfo/checkpassword/
---

# checkPassword(java.lang.String) method

 Checks whether a password is correct for a presentation protected with open password.
 

 
```php
  $info = PresentationFactory->getInstance()->getPresentationInfo($presentationFilePath);
  $isPasswordCorrect = $info->checkPassword("my_password");
```

##  Parameters

| name | description |
| --- | --- |
| password | The password to check. When the password is null or empty, this method returns false. |

##  Returns
True if the presentation is protected with open password and the password is correct and false otherwise.

##  Exception
NotSupportedException if format is not supported to check passwords.


