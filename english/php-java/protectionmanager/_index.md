---
title: ProtectionManager
type: docs
weight: 0
url: /php-java/protectionmanager/
---

# ProtectionManager class

 Presentation password protection management.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [checkWriteProtection](/slides/php-java/protectionmanager/checkwriteprotection/)(String) | boolean | Determines whether a presentation is a password protected to modify. |
| [encrypt](/slides/php-java/protectionmanager/encrypt/)(String) | void | Encrypts Presentation with specified password. |
| [getEncryptDocumentProperties](/slides/php-java/protectionmanager/getencryptdocumentproperties/)() | boolean | This property makes sense, if presentation is password protected. If true then document properties is encrypted in presentation file. If false then document properties is public while presentation is encrypted. Read/write boolean. |
| [getEncryptionPassword](/slides/php-java/protectionmanager/getencryptionpassword/)() | String | Gets the password which is used for presentation encryption. Read-only String. |
| [getReadOnlyRecommended](/slides/php-java/protectionmanager/getreadonlyrecommended/)() | boolean | Gets or sets read-only recommendation. Read/write boolean. |
| [isEncrypted](/slides/php-java/protectionmanager/isencrypted/)() | boolean | Gets a value indicating whether this instance is encrypted. Read-only boolean. Value: true if presentation was loaded from encrypted file or #encrypt(String) method was called ; otherwise, false. |
| [isOnlyDocumentPropertiesLoaded](/slides/php-java/protectionmanager/isonlydocumentpropertiesloaded/)() | boolean | This property makes sense, if presentation file is password protected and document properties of this file are public. Value of true means that only document properties are loaded from an encrypted presentation file without use of password. Value of false means that entire encrypted presentation is loaded with use of right password, not only document properties are loaded. If presentation isn't encrypted then property value is always false. If document properties of an encrypted file aren't public then property value is always false. If Presentation.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded property value is always false. Read-only boolean. |
| [isWriteProtected](/slides/php-java/protectionmanager/iswriteprotected/)() | boolean | Gets a value indicating whether this presentation is write protected. Read-only boolean. |
| [removeEncryption](/slides/php-java/protectionmanager/removeencryption/)() | void | Removes the encryption. |
| [removeWriteProtection](/slides/php-java/protectionmanager/removewriteprotection/)() | void | Removes write protection for this presentation. |
| [setEncryptDocumentProperties](/slides/php-java/protectionmanager/setencryptdocumentproperties/)(boolean) | void | This property makes sense, if presentation is password protected. If true then document properties is encrypted in presentation file. If false then document properties is public while presentation is encrypted. Read/write boolean. |
| [setReadOnlyRecommended](/slides/php-java/protectionmanager/setreadonlyrecommended/)(boolean) | void | Gets or sets read-only recommendation. Read/write boolean. |
| [setWriteProtection](/slides/php-java/protectionmanager/setwriteprotection/)(String) | void | Set write protection for this presentation with specified password. |
