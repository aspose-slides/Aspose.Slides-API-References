---
title: IDigitalSignature
second_title: Aspose.Slides for Java API Reference
description: Digital signature in signed file.
type: docs
url: /ja/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

署名されたファイル内のデジタル署名です。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCertificate()](#getCertificate--) | 文書に署名するために使用された証明書オブジェクトです。 |
| [isValid()](#isValid--) | このデジタル署名が有効で、文書が改ざんされていない場合、この値は true になります。 |
| [getSignTime()](#getSignTime--) | 文書が署名された時刻です。 |
| [getComments()](#getComments--) | 署名の目的です。 |
| [setComments(String value)](#setComments-java.lang.String-) | 署名の目的です。 |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

文書に署名するために使用された証明書オブジェクトです。読み取り専用 byte[]。

**戻り値:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

このデジタル署名が有効で、文書が改ざんされていない場合、この値は true になります。読み取り専用 boolean。

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

**戻り値:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```

文書が署名された時刻です。読み取り専用 java.util.Date。

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

**戻り値:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

署名の目的です。読み書き String。

**戻り値:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

署名の目的です。読み書き String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |