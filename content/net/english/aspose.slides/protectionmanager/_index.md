---
title: ProtectionManager
second_title: Aspose.Sildes for .NET API Reference
description: Presentation password protection management.
type: docs
weight: 9480
url: /aspose.slides/protectionmanager/
---

## ProtectionManager class

Presentation password protection management.

```csharp
public sealed class ProtectionManager : IProtectionManager
```

## Properties

| Name | Description |
| --- | --- |
| [EncryptDocumentProperties](../../aspose.slides/protectionmanager/encryptdocumentproperties) { get; set; } | This property makes sense, if presentation is password protected. If true then document properties is encrypted in presentation file. If false then document properties is public while presentation is encrypted. Read/write Boolean. |
| [EncryptionPassword](../../aspose.slides/protectionmanager/encryptionpassword) { get; } | Gets the password which is used for presentation encryption. Read-only String. |
| [IsEncrypted](../../aspose.slides/protectionmanager/isencrypted) { get; } | Gets a value indicating whether this instance is encrypted. Read-only Boolean. |
| [IsOnlyDocumentPropertiesLoaded](../../aspose.slides/protectionmanager/isonlydocumentpropertiesloaded) { get; } | This property makes sense, if presentation file is password protected and document properties of this file are public. Value of true means that only document properties are loaded from an encrypted presentation file without use of password. Value of false means that entire encrypted presentation is loaded with use of right password, not only document properties are loaded. If presentation isn't encrypted then property value is always false. If document properties of an encrypted file aren't public then property value is always false. If Presentation.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded property value is always false. Read-only Boolean. |
| [IsWriteProtected](../../aspose.slides/protectionmanager/iswriteprotected) { get; } | Gets a value indicating whether this presentation is write protected. Read-only Boolean. |
| [ReadOnlyRecommended](../../aspose.slides/protectionmanager/readonlyrecommended) { get; set; } | Gets or sets read-only recommendation. Read/write Boolean. |

## Methods

| Name | Description |
| --- | --- |
| [CheckWriteProtection](../../aspose.slides/protectionmanager/checkwriteprotection)(string) | Determines whether a presentation is a password protected to modify. |
| [Encrypt](../../aspose.slides/protectionmanager/encrypt)(string) | Encrypts Presentation with specified password. |
| [RemoveEncryption](../../aspose.slides/protectionmanager/removeencryption)() | Removes the encryption. |
| [RemoveWriteProtection](../../aspose.slides/protectionmanager/removewriteprotection)() | Removes write protection for this presentation. |
| [SetWriteProtection](../../aspose.slides/protectionmanager/setwriteprotection)(string) | Set write protection for this presentation with specified password. |

### See Also

* interface [IProtectionManager](../iprotectionmanager)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
