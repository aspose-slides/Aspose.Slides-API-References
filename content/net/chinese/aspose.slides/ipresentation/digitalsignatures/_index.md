---
title: DigitalSignatures
second_title: Aspose.Sildes for .NET API Reference
description: 返回用于签署演示文稿的签名集合。只读 IDigitalSignatureCollection。
type: docs
weight: 90
url: /zh/aspose.slides/ipresentation/digitalsignatures/
---

## IPresentation.DigitalSignatures 属性

返回用于签署演示文稿的签名集合。只读 [`IDigitalSignatureCollection`](../../idigitalsignaturecollection)。

```csharp
public IDigitalSignatureCollection DigitalSignatures { get; }
```

### 示例

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    if (pres.DigitalSignatures.Count > 0)
    {
        bool allSignaturesAreValid = true;

        Console.WriteLine("用于签署演示文稿的签名: ");
        foreach (DigitalSignature signature in pres.DigitalSignatures)
        {
            Console.WriteLine(signature.Certificate.SubjectName.Name + ", "
                    + signature.SignTime.ToString("yyyy-MM-dd HH:mm") + " -- " + (signature.IsValid ? "有效" : "无效"));
            allSignaturesAreValid &= signature.IsValid;
        }

        if (allSignaturesAreValid)
            Console.WriteLine("演示文稿是真实的，所有签名都是有效的。");
        else
            Console.WriteLine("演示文稿在签署后已被修改。");
    }
}
```

### 另见

* 接口 [IDigitalSignatureCollection](../../idigitalsignaturecollection)
* 接口 [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
