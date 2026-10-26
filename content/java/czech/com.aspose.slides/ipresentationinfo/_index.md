---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
description: Informace o souboru prezentace
type: docs
url: /cs/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Informace o souboru prezentace
## Metody

| Metoda | Popis |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Gets True if binded presentation is encrypted, otherwise False. |
| [isPasswordProtected()](#isPasswordProtected--) | Gets a value that indicates whether a binded presentation is protected by a password to open. |
| [isWriteProtected()](#isWriteProtected--) | Gets a value that indicates whether a binded presentation is write protected. |
| [getLoadFormat()](#getLoadFormat--) | Gets format of the binded presentation. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Checks whether a password is correct for a presentation protected with open password. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Checks whether a password to modify is correct for a write protected presentation. |
| [readDocumentProperties()](#readDocumentProperties--) | Gets document properties of binded presentation. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Updates properties of binded presentation. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Writes binded presentation to stream. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Writes binded presentation to file. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Vrací True, pokud je svázaná prezentace šifrována, jinak False. Pouze pro čtení boolean.

**Vrací:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Vrací hodnotu, která udává, zda je svázaná prezentace chráněna heslem pro otevření.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**Vrací:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Vrací hodnotu, která udává, zda je svázaná prezentace chráněna proti zápisu.

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

Pokud je prezentace chráněna heslem pro otevření, hodnota vlastnosti je rovna NotDefined. Viz výčtová hodnota [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Vrací formát svázané prezentace. Pouze pro čtení [LoadFormat](../../com.aspose.slides/loadformat).

**Vrací:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Kontroluje, zda je heslo správné pro prezentaci chráněnou otevřením heslem.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| password | java.lang.String | Heslo k ověření.

--------------------

Když je heslo null nebo prázdné, tato metoda vrací false.

**Vrací:**
boolean – True, pokud je prezentace chráněna otevřením heslem a heslo je správné, jinak false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Kontroluje, zda je heslo pro úpravu správné pro prezentaci chráněnou proti zápisu.

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| password | java.lang.String | Heslo k ověření.

--------------------

1. Měli byste zkontrolovat vlastnost (\#isWriteProtected.isWriteProtected) před voláním této metody. 2. Když je heslo null nebo prázdné, tato metoda vrací false. |

**Vrací:**
boolean – True, pokud je prezentace chráněna proti zápisu a heslo je správné. False jinak.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Vrací vlastnosti dokumentu svázané prezentace.

**Vrací:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Vlastnosti dokumentu [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Aktualizuje vlastnosti svázané prezentace.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Vlastnosti dokumentu [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Zapíše svázanou prezentaci do proudu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Proud musí být vyhledatelný a zapisovatelný. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Zapíše svázanou prezentaci do souboru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Soubor prezentace. |