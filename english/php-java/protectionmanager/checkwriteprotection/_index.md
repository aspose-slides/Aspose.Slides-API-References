---
title: checkWriteProtection
type: docs
weight: 10
url: /php-java/protectionmanager/checkwriteprotection/
---

# checkWriteProtection(java.lang.String) method

 Determines whether a presentation is a password protected to modify.
 

 
```php
  $presentation = new Presentation($presentationFilePath);
  try {
    $isWriteProtected = $presentation->getProtectionManager()->checkWriteProtection("my_password");
  } finally {
    if ($presentation != null) {
      $presentation->dispose();
    }
  }
```

##  Parameters

| name | description |
| --- | --- |
| password | The password for checking. 1. You should check the ( #isWriteProtected) property before calling this method. 2. When the password is null or empty, this method returns false. |

##  Returns
True if the password is valid; otherwise, false.


