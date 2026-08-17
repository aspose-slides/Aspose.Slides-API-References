---
title: DigitalSignature
second_title: Aspose.Slides for Java API 参考
description: 已签名文件中的数字签名。
type: docs
url: /zh/com.aspose.slides/digitalsignature/
---
**继承:**  
java.lang.Object

**已实现的接口:**  
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
>      // 为新的数字签名添加注释
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

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | 使用指定的证书创建一个新的 DigitalSignature 对象。 |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | 使用指定的证书文件路径和密码创建一个新的 DigitalSignature 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCertificate()](#getCertificate--) | 用于签署文档的证书对象。 |
| [isValid()](#isValid--) | 如果此数字签名有效且文档未被篡改，则此值为 true。 |
| [getSignTime()](#getSignTime--) | 文档签署的时间。 |
| [getComments()](#getComments--) | 签名的用途。 |
| [setComments(String value)](#setComments-java.lang.String-) | 签名的用途。 |

### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

使用指定的证书创建一个新的 DigitalSignature 对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certData | byte[] | 包含证书的字节数组 |
| password | java.lang.String | 访问证书所需的密码。 |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

使用指定的证书文件路径和密码创建一个新的 DigitalSignature 对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 证书文件的路径。 |
| password | java.lang.String | 访问证书所需的密码。 |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

用于签署文档的证书对象。只读 byte[]。

**返回值:**
byte[]

### isValid() {#isValid--}
```
public final boolean isValid()
```

如果此数字签名有效且文档未被篡改，则此值为 true。只读 boolean。

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

**返回值:**
boolean

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```

文档签署的时间。只读 java.util.Date。

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


**返回值:**
java.util.Date

### getComments() {#getComments--}
```
public final String getComments()
```

签名的用途。可读写 String。

**返回值:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

签名的用途。可读写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |