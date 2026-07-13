---
title: LoadOptions
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Umożliwia określenie dodatkowych opcji, takich jak format lub domyślna czcionka przy ładowaniu prezentacji.
type: docs
url: /pl/com.aspose.slides/loadoptions/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Umożliwia określenie dodatkowych opcji (takich jak format lub domyślna czcionka) podczas ładowania prezentacji.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Tworzy nowe domyślne opcje ładowania. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Tworzy nowe opcje ładowania. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Zwraca lub ustawia format prezentacji do załadowania. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Zwraca lub ustawia format prezentacji do załadowania. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Zwraca lub ustawia regularną czcionkę używaną, gdy nie znaleziono czcionki źródłowej. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Zwraca lub ustawia regularną czcionkę używaną, gdy nie znaleziono czcionki źródłowej. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Zwraca lub ustawia czcionkę Symbol używaną, gdy nie znaleziono czcionki źródłowej. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Zwraca lub ustawia czcionkę Symbol używaną, gdy nie znaleziono czcionki źródłowej. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Zwraca lub ustawia czcionkę azjatycką używaną, gdy nie znaleziono czcionki źródłowej. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Zwraca lub ustawia czcionkę azjatycką używaną, gdy nie znaleziono czcionki źródłowej. |
| [getPassword()](#getPassword--) | Pobiera lub ustawia hasło. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Pobiera lub ustawia hasło. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem. |
| [getWarningCallback()](#getWarningCallback--) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy przerwany. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy przerwany. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi dużych obiektów binarnych (BLOB), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi dużych obiektów binarnych (BLOB), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Określa źródła zewnętrznych czcionek używanych przez prezentację. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Określa źródła zewnętrznych czcionek używanych przez prezentację. |
| [getInterruptionToken()](#getInterruptionToken--) | Token do monitorowania żądań przerwania. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Token do monitorowania żądań przerwania. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Zwraca lub ustawia interfejs zwrotny, który zarządza ładowaniem zasobów zewnętrznych. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Zwraca lub ustawia interfejs zwrotny, który zarządza ładowaniem zasobów zewnętrznych. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Pobiera opcje dla arkuszy kalkulacyjnych. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Pobiera opcje dla arkuszy kalkulacyjnych. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Zwraca lub ustawia domyślny język tekstu prezentacji. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Zwraca lub ustawia domyślny język tekstu prezentacji. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Tworzy nowe domyślne opcje ładowania.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Tworzy nowe opcje ładowania.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| loadFormat | int | Format prezentacji do załadowania. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Zwraca lub ustawia format prezentacji do załadowania. Odczyt/Zapis [LoadFormat](../../com.aspose.slides/loadformat).

**Zwraca:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Zwraca lub ustawia format prezentacji do załadowania. Odczyt/Zapis [LoadFormat](../../com.aspose.slides/loadformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Zwraca lub ustawia regularną czcionkę używaną, gdy nie znaleziono czcionki źródłowej. Odczyt/Zapis String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Użyj opcji ładowania, aby określić domyślne czcionki regularną i azjatycką
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Wczytaj prezentację
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Wygeneruj miniaturę slajdu
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Wygeneruj PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Wygeneruj XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Zwraca lub ustawia regularną czcionkę używaną, gdy nie znaleziono czcionki źródłowej. Odczyt/Zapis String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Zwraca lub ustawia czcionkę Symbol używaną, gdy nie znaleziono czcionki źródłowej. Odczyt/Zapis String.

**Zwraca:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Zwraca lub ustawia czcionkę Symbol używaną, gdy nie znaleziono czcionki źródłowej. Odczyt/Zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Zwraca lub ustawia czcionkę azjatycką używaną, gdy nie znaleziono czcionki źródłowej. Odczyt/Zapis String.

**Zwraca:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Zwraca lub ustawia czcionkę azjatycką używaną, gdy nie znaleziono czcionki źródłowej. Odczyt/Zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Pobiera lub ustawia hasło. Odczyt/Zapis String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // pracuj z odszyfrowaną prezentacją
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Wartość: Hasło.

**Zwraca:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Pobiera lub ustawia hasło. Odczyt/Zapis String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // pracuj z odszyfrowaną prezentacją
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Wartość: Hasło.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem. Wartość true oznacza, że tylko właściwości dokumentu muszą być załadowane z zaszyfrowanego pliku prezentacji i hasło musi być zignorowane. Wartość false oznacza, że cały zaszyfrowany prezentacja musi być załadowana przy użyciu prawidłowego hasła. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, to właściwości dokumentu nie mogą być załadowane i zostanie rzucony wyjątek. Odczyt/Zapis boolean.

**Zwraca:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem. Wartość true oznacza, że tylko właściwości dokumentu muszą być załadowane z zaszyfrowanego pliku prezentacji i hasło musi być zignorowane. Wartość false oznacza, że cały zaszyfrowany prezentacja musi być załadowana przy użyciu prawidłowego hasła. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, to właściwości dokumentu nie mogą być załadowane i zostanie rzucony wyjątek. Odczyt/Zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy przerwany. Odczyt/Zapis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Zwraca:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy przerwany. Odczyt/Zapis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi dużych obiektów binarnych (BLOB), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. Opcje te mają na celu ustawienie optymalnego stosunku wydajności do zużycia pamięci dla konkretnego środowiska lub wymagań.

--------------------

Obiekt Binary Large Object (BLOB) to dane binarne przechowywane jako pojedynczy byt – czyli BLOB może być dźwiękiem, wideo lub samą prezentacją.

**Zwraca:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi dużych obiektów binarnych (BLOB), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. Opcje te mają na celu ustawienie optymalnego stosunku wydajności do zużycia pamięci dla konkretnego środowiska lub wymagań.

--------------------

Obiekt Binary Large Object (BLOB) to dane binarne przechowywane jako pojedynczy byt – czyli BLOB może być dźwiękiem, wideo lub samą prezentacją.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Określa źródła zewnętrznych czcionek używanych przez prezentację. Czcionki te są dostępne dla prezentacji przez cały jej okres życia i nie są współdzielone z innymi prezentacjami.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //pracuj z prezentacją
>  //CustomFont1, CustomFont2 oraz czcionki z folderów assets\fonts i global\fonts oraz ich podfolderów są dostępne dla prezentacji
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Określa źródła zewnętrznych czcionek używanych przez prezentację. Czcionki te są dostępne dla prezentacji przez cały jej okres życia i nie są współdzielone z innymi prezentacjami.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //pracuj z prezentacją
>  //CustomFont1, CustomFont2 oraz czcionki z folderów assets\fonts i global\fonts oraz ich podfolderów są dostępne dla prezentacji
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Token do monitorowania żądań przerwania.

--------------------

Ten token zarządza całym okresem życia instancji [IPresentation](../../com.aspose.slides/ipresentation). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) obiektu [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Zwraca:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Token do monitorowania żądań przerwania.

--------------------

Ten token zarządza całym okresem życia instancji [IPresentation](../../com.aspose.slides/ipresentation). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) obiektu [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Zwraca lub ustawia interfejs zwrotny, który zarządza ładowaniem zasobów zewnętrznych. Odczyt/Zapis [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Zwraca:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Zwraca lub ustawia interfejs zwrotny, który zarządza ładowaniem zasobów zewnętrznych. Odczyt/Zapis [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Pobiera opcje dla arkuszy kalkulacyjnych. Na przykład, opcje te wpływają na obliczanie formuł dla wykresów.

**Zwraca:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Pobiera opcje dla arkuszy kalkulacyjnych. Na przykład, opcje te wpływają na obliczanie formuł dla wykresów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Zwraca lub ustawia domyślny język tekstu prezentacji. Odczyt/Zapis String.

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
public final void setDefaultTextLanguage(String value)
```

Zwraca lub ustawia domyślny język tekstu prezentacji. Odczyt/Zapis String.

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
public final boolean getDeleteEmbeddedBinaryObjects()
```

Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.

Typy osadzonych obiektów binarnych:

Odczyt/Zapis boolean.

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
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.

Typy osadzonych obiektów binarnych:

Odczyt/Zapis boolean.

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