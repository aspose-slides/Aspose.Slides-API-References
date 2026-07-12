---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Referansı
description: Sunum dosyası hakkında bilgi
type: docs
url: /tr/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Sunum dosyası hakkında bilgi
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Bağlı sunum şifrelenmişse True döndürür, aksi takdirde False. |
| [isPasswordProtected()](#isPasswordProtected--) | Bağlı sunumun açmak için bir parola ile korunup korunmadığını gösteren bir değer getirir. |
| [isWriteProtected()](#isWriteProtected--) | Bağlı sunumun yazma korumalı olup olmadığını gösteren bir değer getirir. |
| [getLoadFormat()](#getLoadFormat--) | Bağlı sunumun formatını getirir. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Açma parolasıyla korunan bir sunum için parolanın doğru olup olmadığını kontrol eder. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Yazma korumalı bir sunum için değiştirme parolasının doğru olup olmadığını kontrol eder. |
| [readDocumentProperties()](#readDocumentProperties--) | Bağlı sunumun belge özelliklerini getirir. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Bağlı sunumun özelliklerini günceller. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Bağlı sunumu akışa yazar. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Bağlı sunumu dosyaya yazar. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Bağlı sunum şifrelenmişse True döndürür, aksi takdirde False. Salt okunur boolean.

**Returns:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Bağlı sunumun açmak için bir parola ile korunup korunmadığını gösteren bir değer getirir.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**Returns:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Bağlı sunumun yazma korumalı olup olmadığını gösteren bir değer getirir.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

Sunum açma parolasıyla korunmuşsa, özellik değeri NotDefined olur. [NullableBool](../../com.aspose.slides/nullablebool) enumuna bakın.

**Returns:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Bağlı sunumun formatını getirir. Salt okunur [LoadFormat](../../com.aspose.slides/loadformat).

**Returns:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Açma parolasıyla korunan bir sunum için parolanın doğru olup olmadığını kontrol eder.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | java.lang.String | Kontrol edilecek parola. |

Parola null veya boş olduğunda, bu yöntem false döndürür.

**Returns:**
boolean - Sunum açma parolasıyla korunuyorsa ve parola doğru ise True, aksi takdirde false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Yazma korumalı bir sunum için değiştirme parolasının doğru olup olmadığını kontrol eder.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | java.lang.String | Kontrol edilecek parola. |

1. Bu yöntemi çağırmadan önce (\#isWriteProtected.isWriteProtected) özelliğini kontrol etmelisiniz. 2. Parola null veya boş olduğunda, bu yöntem false döndürür.

**Returns:**
boolean - Sunum yazma korumalı ve parola doğruysa True. Aksi takdirde False.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Bağlı sunumun belge özelliklerini getirir.

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Belge özellikleri [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Bağlı sunumun özelliklerini günceller.

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

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Belge özellikleri [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Bağlı sunumu akışa yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Akışın aranabilir ve yazılabilir olması gerekir. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Bağlı sunumu dosyaya yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Sunum dosyası. |