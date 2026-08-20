---
title: IDigitalSignature
second_title: Aspose.Slides for Java API Reference
description: 已簽署檔案中的數位簽章。
type: docs
url: /zh-hant/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

已簽署檔案中的數位簽章。

## 方法

| 方法 | 描述 |
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

用於簽署文件的憑證物件。唯讀 byte[].

**返回值:**  
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

如果此數位簽章有效且文件未被竄改，則此值為 true。唯讀 boolean.

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
public abstract Date getSignTime()
```

文件簽署的時間。唯讀 java.util.Date.

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

**返回值:**  
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

簽章的目的。可讀寫 String.

**返回值:**  
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

簽章的目的。可讀寫 String.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |