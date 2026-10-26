---
title: ILoadOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Umożliwia określenie dodatkowych opcji, takich jak format lub domyślna czcionka podczas ładowania prezentacji.
type: docs
url: /pl/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Umożliwia określenie dodatkowych opcji (takich jak format lub domyślna czcionka) podczas ładowania prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Zwraca lub ustawia format prezentacji do załadowania. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Zwraca lub ustawia format prezentacji do załadowania. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Zwraca lub ustawia standardową czcionkę używaną w przypadku, gdy nie znaleziono czcionki źródłowej. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Zwraca lub ustawia standardową czcionkę używaną w przypadku, gdy nie znaleziono czcionki źródłowej. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Zwraca lub ustawia czcionkę Symbol używaną w przypadku, gdy nie znaleziono czcionki źródłowej. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Zwraca lub ustawia czcionkę Symbol używaną w przypadku, gdy nie znaleziono czcionki źródłowej. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Zwraca lub ustawia azjatycką czcionkę używaną w przypadku, gdy nie znaleziono czcionki źródłowej. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Zwraca lub ustawia azjatycką czcionkę używaną w przypadku, gdy nie znaleziono czcionki źródłowej. |
| [getPassword()](#getPassword--) | Pobiera lub ustawia hasło. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Pobiera lub ustawia hasło. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem. |
| [getWarningCallback()](#getWarningCallback--) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi Binary Large Objects (BLOBs), takimi jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi Binary Large Objects (BLOBs), takimi jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Określa źródła zewnętrznych czcionek używanych w prezentacji. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Określa źródła zewnętrznych czcionek używanych w prezentacji. |
| [getInterruptionToken()](#getInterruptionToken--) | Token monitorujący żądania przerwania. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Token monitorujący żądania przerwania. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Zwraca lub ustawia interfejs wywołania zwrotnego, który zarządza ładowaniem zasobów zewnętrznych. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Zwraca lub ustawia interfejs wywołania zwrotnego, który zarządza ładowaniem zasobów zewnętrznych. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Reprezentuje opcje, które mogą być użyte do określenia dodatkowego zachowania arkuszy kalkulacyjnych. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Reprezentuje opcje, które mogą być użyte do określenia dodatkowego zachowania arkuszy kalkulacyjnych. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Zwraca lub ustawia domyślny język tekstu prezentacji. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Zwraca lub ustawia domyślny język tekstu prezentacji. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Zwraca lub ustawia format prezentacji do załadowania. Odczyt/zapis [LoadFormat](../../com.aspose.slides/loadformat).

**Zwraca:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Zwraca lub ustawia format prezentacji do załadowania. Odczyt/zapis [LoadFormat](../../com.aspose.slides/loadformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Zwraca lub ustawia standardową czcionkę używaną w przypadku, gdy nie znaleziono czcionki źródłowej. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Zwraca lub ustawia standardową czcionkę używaną w przypadku, gdy nie znaleziono czcionki źródłowej. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Zwraca lub ustawia czcionkę Symbol używaną w przypadku, gdy nie znaleziono czcionki źródłowej. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Zwraca lub ustawia czcionkę Symbol używaną w przypadku, gdy nie znaleziono czcionki źródłowej. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Zwraca lub ustawia azjatycką czcionkę używaną w przypadku, gdy nie znaleziono czcionki źródłowej. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Zwraca lub ustawia azjatycką czcionkę używaną w przypadku, gdy nie znaleziono czcionki źródłowej. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Pobiera lub ustawia hasło. Odczyt/zapis String.

Value: The password.

**Zwraca:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Pobiera lub ustawia hasło. Odczyt/zapis String.

Value: The password.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem. Wartość true oznacza, że z zaszyfrowanego pliku prezentacji należy załadować tylko właściwości dokumentu, a hasło ma zostać zignorowane. Wartość false oznacza, że cały zaszyfrowany dokument musi być załadowany przy użyciu prawidłowego hasła. Jeśli prezentacja nie jest zaszyfrowana, wartość tej właściwości jest zawsze ignorowana. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość jest true, właściwości nie mogą zostać załadowane i zostanie zgłoszony wyjątek. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem. Wartość true oznacza, że z zaszyfrowanego pliku prezentacji należy załadować tylko właściwości dokumentu, a hasło ma zostać zignorowane. Wartość false oznacza, że cały zaszyfrowany dokument musi być załadowany przy użyciu prawidłowego hasła. Jeśli prezentacja nie jest zaszyfrowana, wartość tej właściwości jest zawsze ignorowana. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość jest true, właściwości nie mogą zostać załadowane i zostanie zgłoszony wyjątek. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Odczyt/zapis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Zwraca:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Odczyt/zapis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi Binary Large Objects (BLOBs), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. Opcje te mają na celu ustawienie najlepszego stosunku wydajności do zużycia pamięci dla konkretnego środowiska lub wymagań.

--------------------

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself.

**Zwraca:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi Binary Large Objects (BLOBs), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. Opcje te mają na celu ustawienie najlepszego stosunku wydajności do zużycia pamięci dla konkretnego środowiska lub wymagań.

--------------------

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Określa źródła zewnętrznych czcionek używanych w prezentacji. Czcionki te są dostępne dla prezentacji przez cały jej czas życia i nie są współdzielone z innymi prezentacjami

**Zwraca:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Określa źródła zewnętrznych czcionek używanych w prezentacji. Czcionki te są dostępne dla prezentacji przez cały jej czas życia i nie są współdzielone z innymi prezentacjami

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Token monitorujący żądania przerwania.

--------------------

Token ten zarządza całym okresem życia instancji [IPresentation](../../com.aspose.slides/ipresentation). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) klasy [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Zwraca:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Token monitorujący żądania przerwania.

--------------------

Token ten zarządza całym okresem życia instancji [IPresentation](../../com.aspose.slides/ipresentation). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) klasy [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |
### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Zwraca lub ustawia interfejs wywołania zwrotnego, który zarządza ładowaniem zasobów zewnętrznych. Odczyt/zapis [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Zwraca:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Zwraca lub ustawia interfejs wywołania zwrotnego, który zarządza ładowaniem zasobów zewnętrznych. Odczyt/zapis [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |
### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Reprezentuje opcje, które mogą być użyte do określenia dodatkowego zachowania arkuszy kalkulacyjnych.

**Zwraca:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Reprezentuje opcje, które mogą być użyte do określenia dodatkowego zachowania arkuszy kalkulacyjnych.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |
### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Zwraca lub ustawia domyślny język tekstu prezentacji. Odczyt/zapis String.

--------------------

> ```
> Example:
>   
>  // Użyj opcji ładowania, aby określić domyślną kulturę tekstu
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Dodaj nowy kształt prostokątny z tekstem
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Sprawdź język pierwszej części
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

Zwraca lub ustawia domyślny język tekstu prezentacji. Odczyt/zapis String.

--------------------

> ```
> Example:
>   
>  // Użyj opcji ładowania, aby określić domyślną kulturę tekstu
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Dodaj nowy prostokątny kształt z tekstem
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Sprawdź język pierwszej części
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.

Typy osadzonych obiektów binarnych:

 *  
 *  
 *  

Odczyt/zapis  boolean .

--------------------

> ```
> Poniższy przykład pokazuje, jak załadować prezentację bez żadnych osadzonych obiektów binarnych.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Domyślnie jest **false**.

**Zwraca:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.

Typy osadzonych obiektów binarnych:

 *  
 *  
 *  

Odczyt/zapis  boolean .

--------------------

> ```
> Poniższy przykład pokazuje, jak załadować prezentację bez żadnych osadzonych obiektów binarnych.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Domyślnie jest **false**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |