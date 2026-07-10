---
title: DigitalSignature
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 已签名文件中的数字签名。
type: docs
url: /zh/com.aspose.slides/digitalsignature/
---
**继承：**
java.lang.Object

**全部实现的接口：**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

已签名文件中的数字签名。

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // 初始化 Presentation 实例
>  Presentation pres = new Presentation();
>  try {
>     // 使用 PFX 文件和 PFX 密码创建 DigitalSignature 对象
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // 为新的数字签名设置注释
>      signature.setComments("Aspose.Slides digital signing test.");
>      // 将数字签名添加到演示文稿
>      pres.getDigitalSignatures().add(signature);
>      // 保存演示文稿
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // 初始化 Presentation 实例
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // 检查所有数字签名是否有效
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>              System.out.println(signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>              allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>              System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>              System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Creates a new DigitalSignature object with the specified certificate. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Creates a new DigitalSignature object with the specified certificate file path and password. |
## Methods

| Method | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | Certificate object that was used to sign the document. |
| [isValid()](#isValid--) | If this digital signature is valid and the document has not been tampered with, this value will be true. |
| [getSignTime()](#getSignTime--) | The time when the document was signed. |
| [getComments()](#getComments--) | The purpose of signature. |
| [setComments(String value)](#setComments-java.lang.String-) | The purpose of signature. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

Creates a new DigitalSignature object with the specified certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certData | byte[] | a byte array containing the certificate |
| password | java.lang.String | Password required to access certificate. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

Creates a new DigitalSignature object with the specified certificate file path and password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Path to the file with certificate. |
| password | java.lang.String | Password required to access certificate. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

Certificate object that was used to sign the document. Read-only byte[].

**Returns:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```
If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only boolean.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```

The time when the document was signed. Read-only java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```

The purpose of signature. Read/write String.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)

签名的目的。可读写的 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |