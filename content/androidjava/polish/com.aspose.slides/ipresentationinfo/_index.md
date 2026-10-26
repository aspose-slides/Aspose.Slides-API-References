---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Informacje o pliku prezentacji
type: docs
url: /pl/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Informacje o pliku prezentacji
## Metody

| Method | Description |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Zwraca True, jeśli powiązana prezentacja jest zaszyfrowana, w przeciwnym razie False. |
| [isPasswordProtected()](#isPasswordProtected--) | Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona hasłem do otwarcia. |
| [isWriteProtected()](#isWriteProtected--) | Zwraca wartość wskazującą, czy powiązana prezentacja jest zabezpieczona przed zapisem. |
| [getLoadFormat()](#getLoadFormat--) | Zwraca format powiązanej prezentacji. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Sprawdza, czy hasło jest poprawne dla prezentacji chronionej hasłem otwarcia. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Sprawdza, czy hasło do modyfikacji jest poprawne dla prezentacji zabezpieczonej przed zapisem. |
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

Zwraca wartość wskazującą, czy powiązana prezentacja jest zabezpieczona przed zapisem.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

Jeśli prezentacja jest chroniona hasłem do otwarcia, wartość właściwości równa się NotDefined. Zobacz wyliczenie [NullableBool](../../com.aspose.slides/nullablebool).

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
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Hasło do sprawdzenia.

--------------------

Gdy hasło jest nullem lub puste, metoda zwraca false.

**Zwraca:**
boolean - True, jeśli prezentacja jest chroniona hasłem otwarcia i hasło jest poprawne, w przeciwnym razie False.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Sprawdza, czy hasło do modyfikacji jest poprawne dla prezentacji zabezpieczonej przed zapisem.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Hasło do sprawdzenia.

--------------------

1. Należy sprawdzić właściwość (\#isWriteProtected.isWriteProtected) przed wywołaniem tej metody. 2. Gdy hasło jest nullem lub puste, metoda zwraca false.

**Zwraca:**
boolean - True, jeśli prezentacja jest zabezpieczona przed zapisem i hasło jest poprawne. False w przeciwnym razie.
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
| Parameter | Type | Description |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Właściwości dokumentu [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Zapisuje powiązaną prezentację do strumienia.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień musi być dostępny do przeszukiwania i zapisu. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Zapisuje powiązaną prezentację do pliku.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Plik prezentacji. |