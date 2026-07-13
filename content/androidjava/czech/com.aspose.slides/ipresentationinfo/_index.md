---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
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
| [isEncrypted()](#isEncrypted--) | Vrátí True, pokud je svázaná prezentace šifrovaná, jinak False. |
| [isPasswordProtected()](#isPasswordProtected--) | Vrátí hodnotu, která udává, zda je svázaná prezentace chráněna heslem pro otevření. |
| [isWriteProtected()](#isWriteProtected--) | Vrátí hodnotu, která udává, zda je svázaná prezentace chráněna proti zápisu. |
| [getLoadFormat()](#getLoadFormat--) | Vrátí formát svázané prezentace. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Kontroluje, zda je heslo správné pro prezentaci chráněnou heslem pro otevření. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Kontroluje, zda je heslo pro úpravy správné pro prezentaci chráněnou proti zápisu. |
| [readDocumentProperties()](#readDocumentProperties--) | Vrátí vlastnosti dokumentu svázané prezentace. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Aktualizuje vlastnosti svázané prezentace. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Zapíše svázanou prezentaci do proudu. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Zapíše svázanou prezentaci do souboru. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Vrátí True, pokud je svázaná prezentace šifrovaná, jinak False. Pouze pro čtení boolean.

**Vrací:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Vrátí hodnotu, která udává, zda je svázaná prezentace chráněna heslem pro otevření.

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

Vrátí hodnotu, která udává, zda je svázaná prezentace chráněna proti zápisu.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

Pokud je prezentace chráněna heslem pro otevření, hodnota vlastnosti se rovná NotDefined. Viz výčtový typ [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Vrátí formát svázané prezentace. Pouze pro čtení [LoadFormat](../../com.aspose.slides/loadformat).

**Vrací:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Kontroluje, zda je heslo správné pro prezentaci chráněnou heslem pro otevření.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| password | java.lang.String | Heslo k ověření. |

--------------------

Když je heslo null nebo prázdné, tato metoda vrátí false. |

**Vrací:**
boolean - True, pokud je prezentace chráněna heslem pro otevření a heslo je správné, a false v opačném případě.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Kontroluje, zda je heslo pro úpravy správné pro prezentaci chráněnou proti zápisu.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| password | java.lang.String | Heslo k ověření. |

--------------------

1. Měli byste zkontrolovat vlastnost (\#isWriteProtected.isWriteProtected) před voláním této metody. 2. Když je heslo null nebo prázdné, tato metoda vrátí false. |

**Vrací:**
boolean - True, pokud je prezentace chráněna proti zápisu a heslo je správné. False v opačném případě.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Vrátí vlastnosti dokumentu svázané prezentace.

**Vrací:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - vlastnosti dokumentu [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | vlastnosti dokumentu [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
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