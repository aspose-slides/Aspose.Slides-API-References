---
title: PresentationInfo
second_title: Aspose.Slides pro Java API Reference
description: Informace o souboru prezentace
type: docs
url: /cs/com.aspose.slides/presentationinfo/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Informace o souboru prezentace
## Metody

| Metoda | Popis |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Vrátí True, pokud je připojená prezentace zašifrována, jinak False. |
| [isPasswordProtected()](#isPasswordProtected--) | Vrátí hodnotu, která udává, zda je připojená prezentace chráněna heslem pro otevření. |
| [isWriteProtected()](#isWriteProtected--) | Vrátí hodnotu, která udává, zda je připojená prezentace chráněna proti zápisu. |
| [getLoadFormat()](#getLoadFormat--) | Vrátí formát připojené prezentace. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Ověří, zda je heslo správné pro prezentaci chráněnou heslem pro otevření. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Ověří, zda je heslo pro úpravy správné pro prezentaci chráněnou proti zápisu. |
| [readDocumentProperties()](#readDocumentProperties--) | Vrátí vlastnosti dokumentu připojené prezentace. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Aktualizuje vlastnosti připojené prezentace. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Zapíše připojenou prezentaci do proudu. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Zapíše připojenou prezentaci do souboru. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Vrátí True, pokud je připojená prezentace zašifrována, jinak False. Pouze pro čtení boolean.

**Vrací:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Vrátí hodnotu, která udává, zda je připojená prezentace chráněna heslem pro otevření.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Vrací:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Vrátí hodnotu, která udává, zda je připojená prezentace chráněna proti zápisu.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


Pokud je prezentace chráněna heslem pro otevření, hodnota vlastnosti se rovná NotDefined.

**Vrací:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Vrátí formát připojené prezentace. Pouze pro čtení [LoadFormat](../../com.aspose.slides/loadformat).

**Vrací:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Ověří, zda je heslo správné pro prezentaci chráněnou heslem pro otevření.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| password | java.lang.String | Heslo k ověření.

Když je heslo null nebo prázdné, tato metoda vrátí false. |

**Vrací:**
boolean - True, pokud je prezentace chráněna heslem pro otevření a heslo je správné, a false v opačném případě.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Ověří, zda je heslo pro úpravy správné pro prezentaci chráněnou proti zápisu.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| password | java.lang.String | Heslo k ověření.

1. Před voláním této metody byste měli zkontrolovat vlastnost (\#isWriteProtected.isWriteProtected). 2. Když je heslo null nebo prázdné, tato metoda vrátí false. |

**Vrací:**
boolean - True, pokud je prezentace chráněna proti zápisu a heslo je správné. False v opačném případě.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Vrátí vlastnosti dokumentu připojené prezentace.

**Vrací:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Aktualizuje vlastnosti připojené prezentace.

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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Zapíše připojenou prezentaci do proudu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Proud musí být posouvatelný a zapisovatelný. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Zapíše připojenou prezentaci do souboru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Soubor prezentace. |