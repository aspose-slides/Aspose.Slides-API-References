---
title: IProtectionManager
second_title: Aspose.Slides for .NET API 参考
description: 演示密码保护管理
type: docs
weight: 6260
url: /zh/net/aspose.slides/iprotectionmanager/
---
## IProtectionManager interface

演示密码保护管理。

```csharp
public interface IProtectionManager
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [EncryptDocumentProperties](../../aspose.slides/iprotectionmanager/encryptdocumentproperties) { get; set; } | 如果演示文稿受密码保护，此属性是有意义的。 如果为真，则文档属性在演示文件中被加密。 如果为 false，则文档属性是公开的，而演示文稿是加密的。 读/写Boolean。 |
| [EncryptionPassword](../../aspose.slides/iprotectionmanager/encryptionpassword) { get; } | 返回加密密码。 只读String。 |
| [IsEncrypted](../../aspose.slides/iprotectionmanager/isencrypted) { get; } | 获取指示此实例是否加密的值。 只读Boolean。 |
| [IsOnlyDocumentPropertiesLoaded](../../aspose.slides/iprotectionmanager/isonlydocumentpropertiesloaded) { get; } | 如果演示文件受密码保护并且文档 该文件的属性是公共的，则此属性是有意义的。 true 的值意味着仅从加密的 演示文件中加载文档属性而不使用密码。 false 值表示使用正确的 密码加载整个加密演示文稿，而不仅仅是加载文档属性。 如果演示文稿未加密，则属性值始终为 false。 如果加密文件的文档属性不公开，则属性值始终为 false。 如果 PresentationEx.EncryptDocumentProperties 为真，则 IsOnlyDocumentPropertiesLoaded 属性值始终为假。 只读Boolean。 |
| [IsWriteProtected](../../aspose.slides/iprotectionmanager/iswriteprotected) { get; } | 获取一个值，该值指示此演示文稿是否受写保护。 只读Boolean。 |
| [ReadOnlyRecommended](../../aspose.slides/iprotectionmanager/readonlyrecommended) { get; set; } | 获取或设置只读推荐。 读/写Boolean。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CheckWriteProtection](../../aspose.slides/iprotectionmanager/checkwriteprotection)(string) | 确定演示文稿是否受密码保护以进行修改。 |
| [Encrypt](../../aspose.slides/iprotectionmanager/encrypt)(string) | 使用指定密码加密演示文稿。 |
| [RemoveEncryption](../../aspose.slides/iprotectionmanager/removeencryption)() | 删除加密。 |
| [RemoveWriteProtection](../../aspose.slides/iprotectionmanager/removewriteprotection)() | 删除此演示文稿的写保护。 |
| [SetWriteProtection](../../aspose.slides/iprotectionmanager/setwriteprotection)(string) | 使用指定密码设置此演示文稿的写保护。 |

### 也可以看看

* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->