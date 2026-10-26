---
title: DigitalSignature
second_title: Aspose.Slides for Android 的 Java API 參考
description: 已簽署檔案中的數位簽章。
type: docs
url: /zh-hant/com.aspose.slides/digitalsignature/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

已簽署檔案中的數位簽章。

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // 初始化 Presentation 實例
>  Presentation pres = new Presentation();
>  try {
>     // 使用 PFX 檔案與 PFX 密碼建立 DigitalSignature 物件
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // 註解新的數位簽章
>      signature.setComments("Aspose.Slides digital signing test.");
>      // 將數位簽章加入簡報
>      pres.getDigitalSignatures().add(signature);
>      // 儲存簡報
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // 初始化 Presentation 實例
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // 檢查所有數位簽章是否有效
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

## 建構子

| 建構子 | 說明 |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | 建立具有指定憑證的新 DigitalSignature 物件。 |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | 建立具有指定憑證檔案路徑和密碼的新 DigitalSignature 物件。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCertificate()](#getCertificate--) | 用於簽署文件的憑證物件。 |
| [isValid()](#isValid--) | 若此數位簽章有效且文件未被竄改，則此值為 true。 |
| [getSignTime()](#getSignTime--) | 文件簽署的時間。 |
| [getComments()](#getComments--) | 簽章的用途。 |
| [setComments(String value)](#setComments-java.lang.String-) | 簽章的用途。 |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


建立具有指定憑證的新 DigitalSignature 物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| certData | byte[] | 包含憑證的位元組陣列 |
| password | java.lang.String | 存取憑證所需的密碼。 |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


建立具有指定憑證檔案路徑和密碼的新 DigitalSignature 物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filePath | java.lang.String | 憑證檔案的路徑。 |
| password | java.lang.String | 存取憑證所需的密碼。 |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


用於簽署文件的憑證物件。唯讀 byte[]。

**傳回值：**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


若此數位簽章有效且文件未被竄改，則此值為 true。唯讀 boolean。

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

**傳回值：**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


文件簽署的時間。唯讀 java.util.Date。

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

**傳回值：**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


簽章的用途。讀寫 String。

**傳回值：**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


簽章的用途。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |