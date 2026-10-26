---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Digital signature in signed file.
type: docs
url: /zh-hant/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

已簽署檔案中的數位簽章。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCertificate()](#getCertificate--) | 用於簽署文件的憑證物件。 |
| [isValid()](#isValid--) | 如果此數位簽章有效且文件未被竄改，則此值為 true。 |
| [getSignTime()](#getSignTime--) | 文件簽署的時間。 |
| [getComments()](#getComments--) | 簽章的目的。 |
| [setComments(String value)](#setComments-java.lang.String-) | 簽章的目的。 |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

用於簽署文件的憑證物件。唯讀 byte[]。

**回傳值：**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

如果此數位簽章有效且文件未被竄改，則此值為 true。唯讀 boolean。

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


**回傳值：**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```

文件簽署的時間。唯讀 java.util.Date。

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


**回傳值：**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

簽章的目的。讀/寫 String。

**回傳值：**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

簽章的目的。讀/寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |