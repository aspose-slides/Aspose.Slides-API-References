---
title: PresentationInfo
second_title: Aspose.Slides for Android Java API Referansı
description: Sunum dosyası hakkında bilgi
type: docs
url: /tr/com.aspose.slides/presentationinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Sunum dosyası hakkında bilgi
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Bağlı sunum şifrelenmişse True, aksi takdirde False döndürür. |
| [isPasswordProtected()](#isPasswordProtected--) | Bağlı sunumun açma parolasıyla korunup korunmadığını gösteren bir değer döndürür. |
| [isWriteProtected()](#isWriteProtected--) | Bağlı sunumun yazma korumalı olup olmadığını gösteren bir değer döndürür. |
| [getLoadFormat()](#getLoadFormat--) | Bağlı sunumun formatını döndürür. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Açma parolasıyla korunan bir sunum için parolanın doğru olup olmadığını kontrol eder. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Yazma korumalı bir sunum için değiştirme parolasının doğru olup olmadığını kontrol eder. |
| [readDocumentProperties()](#readDocumentProperties--) | Bağlı sunumun belge özelliklerini döndürür. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Bağlı sunumun özelliklerini günceller. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Bağlı sunumu akışa yazar. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Bağlı sunumu dosyaya yazar. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Bağlı sunum şifrelenmişse True, aksi takdirde False döndürür. Yalnızca okuma izni olan boolean.

**Döndürür:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Bağlı sunumun açma parolasıyla korunup korunmadığını gösteren bir değer döndürür.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


**Döndürür:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Bağlı sunumun yazma korumalı olup olmadığını gösteren bir değer döndürür.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

Sunum açma parolasıyla korunuyorsa, özellik değeri NotDefined eşittir.

**Döndürür:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Bağlı sunumun formatını döndürür. Yalnızca okuma izni olan [LoadFormat](../../com.aspose.slides/loadformat).

**Döndürür:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Açma parolasıyla korunan bir sunum için parolanın doğru olup olmadığını kontrol eder.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | java.lang.String | Kontrol edilecek parola. |

--------------------

Parola null veya boş olduğunda, bu metod false döndürür. |

**Döndürür:**
boolean - Sunum açma parolasıyla korunuyorsa ve parola doğruysa True, aksi takdirde false.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Yazma korumalı bir sunum için değiştirme parolasının doğru olup olmadığını kontrol eder.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | java.lang.String | Kontrol edilecek parola. |

--------------------

1. Bu metodu çağırmadan önce (\#isWriteProtected.isWriteProtected) özelliğini kontrol etmelisiniz. 2. Parola null veya boş olduğunda, bu metod false döndürür. |

**Döndürür:**
boolean - Sunum yazma korumalı ve parola doğruysa True. Aksi takdirde false.

### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Bağlı sunumun belge özelliklerini döndürür.

**Döndürür:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Bağlı sunumun özelliklerini günceller.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Bağlı sunumu akışa yazar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Akış aranabilir ve yazılabilir olmalıdır. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Bağlı sunumu dosyaya yazar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Sunum dosyası. |