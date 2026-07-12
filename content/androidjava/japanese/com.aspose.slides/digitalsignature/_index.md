---
title: DigitalSignature
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 署名されたファイル内のデジタル署名。
type: docs
url: /ja/com.aspose.slides/digitalsignature/
---
**継承:**
java.lang.Object

**実装されているインターフェイス:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

署名されたファイルのデジタル署名。

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Presentation インスタンスを初期化
>  Presentation pres = new Presentation();
>  try {
>     // PFX ファイルと PFX パスワードで DigitalSignature オブジェクトを作成
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // 新しいデジタル署名にコメントを設定
>      signature.setComments("Aspose.Slides digital signing test.");
>      // プレゼンテーションにデジタル署名を追加
>      pres.getDigitalSignatures().add(signature);
>      // プレゼンテーションを保存
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Presentation インスタンスを初期化
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // すべてのデジタル署名が有効か確認
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

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Creates a new DigitalSignature object with the specified certificate. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Creates a new DigitalSignature object with the specified certificate file path and password. |
## メソッド

| メソッド | 説明 |
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

指定された証明書で新しい DigitalSignature オブジェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| certData | byte[] | 証明書を含むバイト配列 |
| password | java.lang.String | 証明書にアクセスするために必要なパスワード。 |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

指定された証明書ファイルパスとパスワードで新しい DigitalSignature オブジェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 証明書が格納されたファイルへのパス。 |
| password | java.lang.String | 証明書にアクセスするために必要なパスワード。 |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

文書に署名するために使用された証明書オブジェクト。読み取り専用 byte[]。

**戻り値:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
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
public final Date getSignTime()
```

文書が署名された時間。読み取り専用 java.util.Date。

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

**戻り値:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```

署名の目的。読み書き可能 String。

**戻り値:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

署名の目的。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |