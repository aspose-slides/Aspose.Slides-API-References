---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
description: Information about presentation file
type: docs
url: /pl/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Informacje o pliku prezentacji
## Metody

| Metoda | Opis |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Zwraca True, jeśli powiązana prezentacja jest zaszyfrowana, w przeciwnym razie False. |
| [isPasswordProtected()](#isPasswordProtected--) | Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona hasłem do otwarcia. |
| [isWriteProtected()](#isWriteProtected--) | Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona przed zapisem. |
| [getLoadFormat()](#getLoadFormat--) | Zwraca format powiązanej prezentacji. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Sprawdza, czy hasło jest poprawne dla prezentacji chronionej hasłem otwarcia. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Sprawdza, czy hasło modyfikacji jest poprawne dla prezentacji chronionej przed zapisem. |
| [readDocumentProperties()](#readDocumentProperties--) | Zwraca właściwości dokumentu powiązanej prezentacji. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Aktualizuje właściwości powiązanej prezentacji. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Zapisuje powiązaną prezentację do strumienia. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Zapisuje powiązaną prezentację do pliku. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Zwraca True, jeśli powiązana prezentacja jest zaszyfrowana, w przeciwnym razie False. Tylko do odczytu boolean.

**Zwraca:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona hasłem do otwarcia.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**Zwraca:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona przed zapisem.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

Jeśli prezentacja jest chroniona hasłem do otwarcia, wartość właściwości równa się NotDefined. Zobacz [NullableBool](../../com.aspose.slides/nullablebool) enumerację.

**Zwraca:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Zwraca format powiązanej prezentacji. Tylko do odczytu [LoadFormat](../../com.aspose.slides/loadformat).

**Zwraca:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Sprawdza, czy hasło jest poprawne dla prezentacji chronionej hasłem otwarcia.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| password | java.lang.String | Hasło do sprawdzenia. |

--------------------

Gdy hasło jest null lub puste, metoda zwraca false.

**Zwraca:**
boolean - True, jeśli prezentacja jest chroniona hasłem otwarcia i hasło jest poprawne, w przeciwnym razie false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Sprawdza, czy hasło modyfikacji jest poprawne dla prezentacji chronionej przed zapisem.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| password | java.lang.String | Hasło do sprawdzenia. |

--------------------

1. Należy sprawdzić właściwość (\#isWriteProtected.isWriteProtected) przed wywołaniem tej metody. 2. Gdy hasło jest null lub puste, metoda zwraca false.

**Zwraca:**
boolean - True, jeśli prezentacja jest chroniona przed zapisem i hasło jest poprawne. False w przeciwnym razie.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Zwraca właściwości dokumentu powiązanej prezentacji.

**Zwraca:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Właściwości dokumentu [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Aktualizuje właściwości powiązanej prezentacji.

--------------------

> ```
> Ten przykład pokazuje, jak wywołać metodę #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) aby
>  zaktualizować właściwości dokumentu zwrócone przez wywołanie metody #readDocumentProperties.readDocumentProperties.
>  
>  IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Właściwości dokumentu [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Zapisuje powiązaną prezentację do strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień musi być seekable i zapisywalny. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Zapisuje powiązaną prezentację do pliku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| file | java.lang.String | Plik prezentacji. |