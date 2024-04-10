---
title: ProtectionManager class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## ProtectionManager class

Presentation password protection management.

The ProtectionManager type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [encrypt_document_properties](/slides/python-net/aspose.slides/encrypt_document_properties) | This property makes sense, if presentation is password protected.<br/>            If true then document properties is encrypted in presentation file.<br/>            If false then document properties is public while presentation is encrypted.<br/>            Read/write :py:class:`bool`. |
| [is_encrypted](/slides/python-net/aspose.slides/is_encrypted) | Gets a value indicating whether this instance is encrypted.<br/>            Read-only :py:class:`bool`. |
| [is_only_document_properties_loaded](/slides/python-net/aspose.slides/is_only_document_properties_loaded) | This property makes sense, if presentation file is password protected and document <br/>            properties of this file are public.<br/>            Value of true means that only document properties are loaded from an encrypted <br/>            presentation file without use of password.<br/>            Value of false means that entire encrypted presentation is loaded with use of right <br/>            password, not only document properties are loaded.<br/>            If presentation isn't encrypted then property value is always false.<br/>            If document properties of an encrypted file aren't public then property value is always false.<br/>            If Presentation.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded <br/>            property value is always false.<br/>            Read-only :py:class:`bool`. |
| [is_write_protected](/slides/python-net/aspose.slides/is_write_protected) | Gets a value indicating whether this presentation is write protected.<br/>            Read-only :py:class:`bool`. |
| [encryption_password](/slides/python-net/aspose.slides/encryption_password) | Gets the password which is used for presentation encryption.<br/>            Read-only :py:class:`System.String`. |
| [read_only_recommended](/slides/python-net/aspose.slides/read_only_recommended) | Gets or sets read-only recommendation.<br/>            Read/write :py:class:`bool`. |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/protectionmanager/#string) | Encrypts Presentation with specified password. |
| [__init__](/slides/python-net/aspose.slides/protectionmanager/#) | Removes the encryption. |
| [__init__](/slides/python-net/aspose.slides/protectionmanager/#string) | Set write protection for this presentation with specified password. |
| [__init__](/slides/python-net/aspose.slides/protectionmanager/#) | Removes write protection for this presentation. |
| [__init__](/slides/python-net/aspose.slides/protectionmanager/#string) | Determines whether a presentation is a password protected to modify. |

