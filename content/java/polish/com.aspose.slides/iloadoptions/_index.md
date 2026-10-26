---
title: ILoadOptions
second_title: Aspose.Slides for Java API Reference
description: Allows to specify additional options such as format or default font when loading a presentation.
type: docs
url: /pl/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Umożliwia określenie dodatkowych opcji (takich jak format lub domyślna czcionka) podczas ładowania prezentacji.
## Methods

| Method | Description |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Zwraca lub ustawia format prezentacji do załadowania. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Zwraca lub ustawia format prezentacji do załadowania. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Zwraca lub ustawia regularną czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Zwraca lub ustawia regularną czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Zwraca lub ustawia czcionkę Symbol używaną, gdy nie zostanie znaleziona czcionka źródłowa. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Zwraca lub ustawia czcionkę Symbol używaną, gdy nie zostanie znaleziona czcionka źródłowa. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Zwraca lub ustawia azjatycką czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Zwraca lub ustawia azjatycką czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. |
| [getPassword()](#getPassword--) | Pobiera lub ustawia hasło. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Pobiera lub ustawia hasło. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem. |
| [getWarningCallback()](#getWarningCallback--) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Reprezentuje opcje, które można użyć do zarządzania zachowaniem obsługi Binary Large Objects (BLOBów), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Reprezentuje opcje, które można użyć do zarządzania zachowaniem obsługi Binary Large Objects (BLOBów), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Określa źródła zewnętrznych czcionek używanych przez prezentację. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Określa źródła zewnętrznych czcionek używanych przez prezentację. |
| [getInterruptionToken()](#getInterruptionToken--) | Token do monitorowania żądań przerwania. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Token do monitorowania żądań przerwania. |
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

Zwraca lub ustawia regularną czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Zwraca lub ustawia regularną czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Zwraca lub ustawia czcionkę Symbol używaną, gdy nie zostanie znaleziona czcionka źródłowa. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Zwraca lub ustawia czcionkę Symbol używaną, gdy nie zostanie znaleziona czcionka źródłowa. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Zwraca lub ustawia azjatycką czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Zwraca lub ustawia azjatycką czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Pobiera lub ustawia hasło. Odczyt/zapis String.

Wartość: Hasło.

**Zwraca:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Pobiera lub ustawia hasło. Odczyt/zapis String.

Wartość: Hasło.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem. Wartość true oznacza, że z zaszyfrowanego pliku prezentacji należy załadować tylko właściwości dokumentu i hasło ma być pominięte. Wartość false oznacza, że cała zaszyfrowana prezentacja musi być załadowana przy użyciu właściwego hasła. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, właściwości dokumentu nie mogą być załadowane i zostanie zgłoszony wyjątek. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem. Wartość true oznacza, że z zaszyfrowanego pliku prezentacji należy załadować tylko właściwości dokumentu i hasło ma być pominięte. Wartość false oznacza, że cała zaszyfrowana prezentacja musi być załadowana przy użyciu właściwego hasła. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, właściwości dokumentu nie mogą być załadowane i zostanie zgłoszony wyjątek. Odczyt/zapis boolean.

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

Reprezentuje opcje, które można użyć do zarządzania zachowaniem obsługi Binary Large Objects (BLOBów), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. Te opcje mają na celu ustawienie najlepszego stosunku wydajność/pamięć dla określonego środowiska lub wymagań.

--------------------

Binary Large Object (BLOB) to dane binarne przechowywane jako pojedynczy podmiot – np. BLOB może być dźwiękiem, wideo lub samą prezentacją.

**Zwraca:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Reprezentuje opcje, które można użyć do zarządzania zachowaniem obsługi Binary Large Objects (BLOBów), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. Te opcje mają na celu ustawienie najlepszego stosunku wydajność/pamięć dla określonego środowiska lub wymagań.

--------------------

Binary Large Object (BLOB) to dane binarne przechowywane jako pojedynczy podmiot – np. BLOB może być dźwiękiem, wideo lub samą prezentacją.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Określa źródła zewnętrznych czcionek używanych przez prezentację. Czcionki te są dostępne dla prezentacji przez cały jej okres życia i nie są współdzielone z innymi prezentacjami.

**Zwraca:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Określa źródła zewnętrznych czcionek używanych przez prezentację. Czcionki te są dostępne dla prezentacji przez cały jej okres życia i nie są współdzielone z innymi prezentacjami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Token do monitorowania żądań przerwania.

--------------------

Token zarządza całym okresem życia instancji [IPresentation](../../com.aspose.slides/ipresentation). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) z [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Zwraca:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Token do monitorowania żądań przerwania.

--------------------

Token zarządza całym okresem życia instancji [IPresentation](../../com.aspose.slides/ipresentation). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) z [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

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
>      // Dodaj nowy prostokątny kształt z tekstem
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

Odczyt/zapis boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
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

Odczyt/zapis boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
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