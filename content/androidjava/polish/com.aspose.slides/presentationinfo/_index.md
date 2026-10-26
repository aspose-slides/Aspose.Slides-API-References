---
title: PresentationInfo
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Informacje o pliku prezentacji
type: docs
url: /pl/com.aspose.slides/presentationinfo/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Informacje o pliku prezentacji
## Metody

| Metoda | Opis |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Zwraca True, jeśli powiązana prezentacja jest zaszyfrowana, w przeciwnym razie False. |
| [isPasswordProtected()](#isPasswordProtected--) | Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona hasłem przy otwieraniu. |
| [isWriteProtected()](#isWriteProtected--) | Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona przed zapisem. |
| [getLoadFormat()](#getLoadFormat--) | Zwraca format powiązanej prezentacji. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Sprawdza, czy hasło jest poprawne dla prezentacji chronionej hasłem otwarcia. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Sprawdza, czy hasło do modyfikacji jest poprawne dla prezentacji chronionej przed zapisem. |
| [readDocumentProperties()](#readDocumentProperties--) | Zwraca właściwości dokumentu powiązanej prezentacji. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Aktualizuje właściwości powiązanej prezentacji. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Zapisuje powiązaną prezentację do strumienia. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Zapisuje powiązaną prezentację do pliku. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Zwraca True, jeśli powiązana prezentacja jest zaszyfrowana, w przeciwnym razie False. Tylko do odczytu boolean.

**Zwraca:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona hasłem przy otwieraniu.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


**Zwraca:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona przed zapisem.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

Jeśli prezentacja jest chroniona hasłem przy otwieraniu, wartość właściwości równa się NotDefined.

**Zwraca:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Zwraca format powiązanej prezentacji. Tylko do odczytu [LoadFormat](../../com.aspose.slides/loadformat).

**Zwraca:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Sprawdza, czy hasło jest poprawne dla prezentacji chronionej hasłem otwarcia.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| password | java.lang.String | Hasło do sprawdzenia.

--------------------

Gdy hasło jest null lub puste, metoda zwraca false.

**Zwraca:**
boolean - True, jeśli prezentacja jest chroniona hasłem otwarcia i hasło jest poprawne, oraz false w przeciwnym wypadku.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Sprawdza, czy hasło do modyfikacji jest poprawne dla prezentacji chronionej przed zapisem.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| password | java.lang.String | Hasło do sprawdzenia.

--------------------

1. Należy sprawdzić właściwość (\#isWriteProtected.isWriteProtected) przed wywołaniem tej metody. 2. Gdy hasło jest null lub puste, metoda zwraca false.

**Zwraca:**
boolean - True, jeśli prezentacja jest chroniona przed zapisem i hasło jest poprawne. False w przeciwnym wypadku.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Zwraca właściwości dokumentu powiązanej prezentacji.

**Zwraca:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Aktualizuje właściwości powiązanej prezentacji.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Zapisuje powiązaną prezentację do strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień musi być możliwy do przeszukania i zapisu. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Zapisuje powiązaną prezentację do pliku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| file | java.lang.String | Plik prezentacji. |