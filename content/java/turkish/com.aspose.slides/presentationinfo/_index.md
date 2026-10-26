---
title: PresentationInfo
second_title: Aspose.Slides for Java API Referansı
description: Sunum dosyası hakkında bilgi
type: docs
url: /tr/com.aspose.slides/presentationinfo/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Sunum dosyası hakkında bilgi
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Bağlanmış sunum şifreli ise True, aksi takdirde False döndürür. |
| [isPasswordProtected()](#isPasswordProtected--) | Bağlanmış sunumun açmak için bir şifreyle korunup korunmadığını belirten bir değer döndürür. |
| [isWriteProtected()](#isWriteProtected--) | Bağlanmış sunumun yazma korumalı olup olmadığını belirten bir değer döndürür. |
| [getLoadFormat()](#getLoadFormat--) | Bağlanmış sunumun formatını döndürür. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Açma şifresiyle korunan bir sunum için şifrenin doğru olup olmadığını denetler. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Yazma korumalı bir sunum için değiştirme şifresinin doğru olup olmadığını denetler. |
| [readDocumentProperties()](#readDocumentProperties--) | Bağlanmış sunumun belge özelliklerini döndürür. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Bağlanmış sunumun özelliklerini günceller. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Bağlanmış sunumu akışa yazar. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Bağlanmış sunumu dosyaya yazar. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Bağlanmış sunum şifreli ise True, aksi takdirde False döndürür. Yalnızca okuma boolean.

**Döndürür:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Bağlanmış sunumun açmak için bir şifreyle korunup korunmadığını belirten bir değer döndürür.

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

Bağlanmış sunumun yazma korumalı olup olmadığını belirten bir değer döndürür.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

Sunum açma şifresiyle korunuyorsa, özellik değeri NotDefined olur.

**Döndürür:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Bağlanmış sunumun formatını döndürür. Yalnızca okuma [LoadFormat](../../com.aspose.slides/loadformat).

**Döndürür:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Açma şifresiyle korunan bir sunum için şifrenin doğru olup olmadığını denetler.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | java.lang.String | Kontrol edilecek şifre. |

Şifre null veya boş olduğunda, bu metod false döndürür.

**Döndürür:**
boolean - Sunum açma şifresiyle korunuyorsa ve şifre doğruysa True, aksi takdirde false.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Yazma korumalı bir sunum için değiştirme şifresinin doğru olup olmadığını denetler.

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
| password | java.lang.String | Kontrol edilecek şifre. |

1. Bu metodu çağırmadan önce (\#isWriteProtected.isWriteProtected) özelliğini kontrol etmelisiniz. 2. Şifre null veya boş olduğunda, bu metod false döndürür.

**Döndürür:**
boolean - Sunum yazma korumalıysa ve şifre doğruysa True. Aksi takdirde False.

### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Bağlanmış sunumun belge özelliklerini döndürür.

**Döndürür:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Bağlanmış sunumun özelliklerini günceller.

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

Bağlanmış sunumu akışa yazar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Akış aranabilir ve yazılabilir olmalıdır. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Bağlanmış sunumu dosyaya yazar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Sunum dosyası. |