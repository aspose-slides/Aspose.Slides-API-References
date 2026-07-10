---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: 已签名文件中的数字签名。
type: docs
url: /zh/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

已签名文件中的数字签名。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCertificate()](#getCertificate--) | 用于对文档签名的证书对象。 |
| [isValid()](#isValid--) | 如果此数字签名有效且文档未被篡改，则此值为 true。 |
| [getSignTime()](#getSignTime--) | 文档签署的时间。 |
| [getComments()](#getComments--) | 签名的目的。 |
| [setComments(String value)](#setComments-java.lang.String-) | 签名的目的。 |

### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

用于对文档签名的证书对象。只读 byte[]。

**返回：**
byte[]

### isValid() {#isValid--}
```
public abstract boolean isValid()
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

**Returns:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```

The time when the document was signed. Read-only java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.IsValid ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

The purpose of signature. Read/write String.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)

签名的目的。可读写 String。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | java.lang.String |  |