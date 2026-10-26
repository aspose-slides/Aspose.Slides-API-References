---
title: LoadOptions
second_title: Aspose.Slides Java API referencia
description: Lehetővé teszi további beállítások megadását, például formátum vagy alapértelmezett betűtípus megadását egy prezentáció betöltésekor.
type: docs
url: /hu/com.aspose.slides/loadoptions/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Lehetővé teszi további beállítások megadását (például formátum vagy alapértelmezett betűtípus) egy prezentáció betöltésekor.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Új alapértelmezett betöltési beállításokat hoz létre. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Új betöltési beállításokat hoz létre. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Visszaadja vagy beállítja a betöltendő prezentáció formátumát. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Visszaadja vagy beállítja a betöltendő prezentáció formátumát. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Visszaadja vagy beállítja a szabályos betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Visszaadja vagy beállítja a szabályos betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Visszaadja vagy beállítja a szimbólum betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Visszaadja vagy beállítja a szimbólum betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Visszaadja vagy beállítja az ázsiai betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Visszaadja vagy beállítja az ázsiai betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. |
| [getPassword()](#getPassword--) | Lekéri vagy beállítja a jelszót. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Lekéri vagy beállítja a jelszót. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Ez a tulajdonság értelmes, ha a prezentációfájl jelszóval védett. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Ez a tulajdonság értelmes, ha a prezentációfájl jelszóval védett. |
| [getWarningCallback()](#getWarningCallback--) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad-e. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad-e. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | A bináris nagy objektumok (BLOB-ok) kezelésének viselkedését szabályozó beállításokat képviseli, például ideiglenes fájlok használatát vagy a memóriában tárolható maximális BLOB bájt számot. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | A bináris nagy objektumok (BLOB-ok) kezelésének viselkedését szabályozó beállításokat képviseli, például ideiglenes fájlok használatát vagy a memóriában tárolható maximális BLOB bájt számot. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Megadja a prezentáció által használandó külső betűtípusok forrásait. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Megadja a prezentáció által használandó külső betűtípusok forrásait. |
| [getInterruptionToken()](#getInterruptionToken--) | Az token, amelyet megszakítási kérések figyelésére használnak. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Az token, amelyet megszakítási kérések figyelésére használnak. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Visszaadja vagy beállítja azt a visszahívási interfészt, amely a külső erőforrások betöltését kezeli. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Visszaadja vagy beállítja azt a visszahívási interfészt, amely a külső erőforrások betöltését kezeli. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Lekéri a táblázatok beállításait. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Lekéri a táblázatok beállításait. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltése során. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltése során. |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Új alapértelmezett betöltési beállításokat hoz létre.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Új betöltési beállításokat hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| loadFormat | int | A betöltendő prezentáció formátuma. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Visszaadja vagy beállítja a betöltendő prezentáció formátumát. Olvasás/írás [LoadFormat](../../com.aspose.slides/loadformat).

**Visszatér:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Visszaadja vagy beállítja a betöltendő prezentáció formátumát. Olvasás/írás [LoadFormat](../../com.aspose.slides/loadformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Visszaadja vagy beállítja a szabályos betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. Olvasás/írás String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Használja a betöltési beállításokat az alapértelmezett szabályos és ázsiai betűtípusok meghatározásához
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Töltsük be a prezentációt
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Dia bélyegkép generálása
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // PDF generálása
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS generálása
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Visszaadja vagy beállítja a szabályos betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. Olvasás/írás String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Használja a betöltési beállításokat az alapértelmezett szabályos és ázsiai betűtípusok meghatározásához
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Töltsük be a prezentációt
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Dia bélyegkép generálása
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // PDF generálása
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS generálása
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Visszaadja vagy beállítja a szimbólum betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Visszaadja vagy beállítja a szimbólum betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Visszaadja vagy beállítja az ázsiai betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Visszaadja vagy beállítja az ázsiai betűtípust, amelyet a forrás betűtípus hiánya esetén használnak. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Lekéri vagy beállítja a jelszót. Olvasás/írás String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // munkázzon a feloldott prezentációval
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Érték: A jelszó.

**Visszatér:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Lekéri vagy beállítja a jelszót. Olvasás/írás String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // munkázzon a feloldott prezentációval
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Érték: A jelszó.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Ez a tulajdonság értelmes, ha a prezentációfájl jelszóval védett. A true érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni egy titkosított prezentációfájlból, a jelszót figyelmen kívül hagyva. A false érték azt jelenti, hogy a teljes titkosított prezentációt a megfelelő jelszóval kell betölteni. Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak és a tulajdonság értéke true, akkor a dokumentumtulajdonságok nem tölthetők be, és kivétel keletkezik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Ez a tulajdonság értelmes, ha a prezentációfájl jelszóval védett. A true érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni egy titkosított prezentációfájlból, a jelszót figyelmen kívül hagyva. A false érték azt jelenti, hogy a teljes titkosított prezentációt a megfelelő jelszóval kell betölteni. Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak és a tulajdonság értéke true, akkor a dokumentumtulajdonságok nem tölthetők be, és kivétel keletkezik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad-e. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Visszatér:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad-e. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

A bináris nagy objektumok (BLOB-ok) kezelésének viselkedését szabályozó beállításokat képviseli, például ideiglenes fájlok használatát vagy a memóriában tárolható maximális BLOB bájt számot. Ezek a beállítások a legjobb teljesítmény-/memória-használati arány elérését célozzák egy adott környezetben vagy követelmény esetén.

--------------------

A Binary Large Object (BLOB) egy bináris adat, amely egyetlen entitásként tárolódik – például BLOB lehet egy hang, videó vagy maga a prezentáció.

**Visszatér:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

A bináris nagy objektumok (BLOB-ok) kezelésének viselkedését szabályozó beállításokat képviseli, például ideiglenes fájlok használatát vagy a memóriában tárolható maximális BLOB bájt számot. Ezek a beállítások a legjobb teljesítmény-/memória-használati arány elérését célozzák egy adott környezetben vagy követelmény esetén.

--------------------

A Binary Large Object (BLOB) egy bináris adat, amely egyetlen entitásként tárolódik – például BLOB lehet egy hang, videó vagy maga a prezentáció.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Megadja a prezentáció által használandó külső betűtípusok forrásait. Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztoznak más prezentációk között.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //munkázzon a prezentációval
>  //A CustomFont1, CustomFont2, valamint az assets\fonts & global\fonts mappák és almappáik betűtípusai elérhetők a prezentációban
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Megadja a prezentáció által használandó külső betűtípusok forrásait. Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztoznak más prezentációk között.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //munkázzon a prezentációval
>  //CustomFont1, CustomFont2, valamint az assets\fonts & global\fonts mappák és almappáik betűtípusai elérhetők a prezentációban
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Az token, amelyet megszakítási kérések figyelésére használnak.

--------------------

Ez a token kezeli a teljes [IPresentation](../../com.aspose.slides/ipresentation) példány életciklusát. Bármely hosszú művelet, például a prezentáció betöltése vagy mentése, az [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) metódus meghívásával lesz megszakítva a [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)-n.

**Visszatér:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Az token, amelyet megszakítási kérések figyelésére használnak.

--------------------

Ez a token kezeli a teljes [IPresentation](../../com.aspose.slides/ipresentation) példány életciklusát. Bármely hosszú művelet, például a prezentáció betöltése vagy mentése, az [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) metódus meghívásával lesz megszakítva a [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)-n.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Visszaadja vagy beállítja azt a visszahívási interfészt, amely a külső erőforrások betöltését kezeli. Olvasás/írás [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Visszatér:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Visszaadja vagy beállítja azt a visszahívási interfészt, amely a külső erőforrások betöltését kezeli. Olvasás/írás [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Lekéri a táblázatok beállításait. Például ezek a beállítások befolyásolják a diagramok képleteinek számítását.

**Visszatér:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Lekéri a táblázatok beállításait. Például ezek a beállítások befolyásolják a diagramok képleteinek számítását.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. Olvasás/írás String.

--------------------

> ```
> Example:
>   
>  // Használja a betöltési beállításokat az alapértelmezett szövegkultúra meghatározásához
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Új téglalap alakzat hozzáadása szöveggel
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Ellenőrizze az első rész nyelvét
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. Olvasás/írás String.

--------------------

> ```
> Example:
>   
>  // Használja a betöltési beállításokat az alapértelmezett szövegkultúra meghatározásához
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Új téglalap alakzat hozzáadása szöveggel
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Ellenőrizze az első rész nyelvét
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltése során.

A beágyazott bináris objektumok típusai:

Olvasás/írás  boolean .

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

Az alapértelmezett **false** .

**Visszatér:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltése során.

A beágyazott bináris objektumok típusai:

Olvasás/írás  boolean .

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

Az alapértelmezett **false** .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |