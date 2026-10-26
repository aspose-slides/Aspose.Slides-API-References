---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
description: Information about presentation file
type: docs
url: /tr/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Sunum dosyası hakkında bilgi
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Bağlı sunum şifrelenmişse True, aksi takdirde False döndürür. |
| [isPasswordProtected()](#isPasswordProtected--) | Bağlı sunumun açmak için parola ile korunup korunmadığını gösteren bir değer döndürür. |
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
public abstract boolean isEncrypted()
```

Bağlı sunum şifrelenmişse True, aksi takdirde False döndürür. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Bağlı sunumun açmak için parola ile korunup korunmadığını gösteren bir değer döndürür.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**Döndürür:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Bağlı sunumun yazma korumalı olup olmadığını gösteren bir değer döndürür.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

If the presentation is protected by a password to open, the property value equals NotDefined. See [NullableBool](../../com.aspose.slides/nullablebool) enumeration.

**Döndürür:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Bağlı sunumun formatını döndürür. Yalnızca okunabilir [LoadFormat](../../com.aspose.slides/loadformat).

**Döndürür:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Açma parolasıyla korunan bir sunum için parolanın doğru olup olmadığını kontrol eder.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| password | java.lang.String | Kontrol edilecek parola.

When the password is null or empty, this method returns false. |

**Döndürür:**
boolean - Sunum açma parolasıyla korunuyorsa ve parola doğruysa True, aksi takdirde false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Yazma korumalı bir sunum için değiştirme parolasının doğru olup olmadığını kontrol eder.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| password | java.lang.String | Kontrol edilecek parola.

1. Bu metodu çağırmadan önce (\#isWriteProtected.isWriteProtected) özelliğini kontrol etmelisiniz. 2. Parola null ya da boş ise, bu metot false döndürür. |

**Döndürür:**
boolean - Sunum yazma korumalı ve parola doğruysa True. Aksi takdirde False.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Bağlı sunumun belge özelliklerini döndürür.

**Döndürür:**
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

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Belge özellikleri [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Bağlı sunumu akışa yazar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Akışın aranabilir ve yazılabilir olması gerekir. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Bağlı sunumu dosyaya yazar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Sunum dosyası. |