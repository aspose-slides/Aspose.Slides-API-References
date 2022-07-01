---
title: ProtectionManager
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/protectionmanager/
---

## ProtectionManager class

 Presentation password protection management.
 

## Methods

| Name | Description |
| --- | --- |
| [checkWriteProtection](checkwriteprotection)(String) | Determines whether a presentation is a password protected to modify. |
| [encrypt](encrypt)(String) | Encrypts Presentation with specified password. |
| [getEncryptDocumentProperties](getencryptdocumentproperties)() | This property makes sense, if presentation is password protected. If true then document properties is encrypted in presentation file. If false then document properties is public while presentation is encrypted. Read/write boolean. |
| [getEncryptionPassword](getencryptionpassword)() | Gets the password which is used for presentation encryption. Read-only String. |
| [getReadOnlyRecommended](getreadonlyrecommended)() | Gets or sets read-only recommendation. Read/write boolean. |
| [isEncrypted](isencrypted)() | Gets a value indicating whether this instance is encrypted. Read-only boolean. Value: true if presentation was loaded from encrypted file or #encrypt(String) method was called ; otherwise, false. |
| [isOnlyDocumentPropertiesLoaded](isonlydocumentpropertiesloaded)() | This property makes sense, if presentation file is password protected and document properties of this file are public. Value of true means that only document properties are loaded from an encrypted presentation file without use of password. Value of false means that entire encrypted presentation is loaded with use of right password, not only document properties are loaded. If presentation isn't encrypted then property value is always false. If document properties of an encrypted file aren't public then property value is always false. If Presentation.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded property value is always false. Read-only boolean. |
| [isWriteProtected](iswriteprotected)() | Gets a value indicating whether this presentation is write protected. Read-only boolean. |
| [removeEncryption](removeencryption)() | Removes the encryption. |
| [removeWriteProtection](removewriteprotection)() | Removes write protection for this presentation. |
| [setEncryptDocumentProperties](setencryptdocumentproperties)(boolean) | This property makes sense, if presentation is password protected. If true then document properties is encrypted in presentation file. If false then document properties is public while presentation is encrypted. Read/write boolean. |
| [setReadOnlyRecommended](setreadonlyrecommended)(boolean) | Gets or sets read-only recommendation. Read/write boolean. |
| [setWriteProtection](setwriteprotection)(String) | Set write protection for this presentation with specified password. |
