---
title: LoadOptions
second_title: Aspose.Slides Androidra vonatkozó Java API referencia
description: Lehetővé teszi további beállítások megadását, például formátum vagy alapértelmezett betűtípus megadását a prezentáció betöltésekor.
type: docs
url: /hu/com.aspose.slides/loadoptions/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Lehetővé teszi további beállítások (például formátum vagy alapértelmezett betűtípus) megadását a prezentáció betöltésekor.
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
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Visszaadja vagy beállítja a Regular betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Visszaadja vagy beállítja a Regular betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Visszaadja vagy beállítja a Symbol betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Visszaadja vagy beállítja a Symbol betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Visszaadja vagy beállítja az Asian betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Visszaadja vagy beállítja az Asian betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. |
| [getPassword()](#getPassword--) | Lekéri vagy beállítja a jelszót. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Lekéri vagy beállítja a jelszót. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Ez a tulajdonság akkor érvényes, ha a prezentáció fájl jelszóval védett. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Ez a tulajdonság akkor érvényes, ha a prezentáció fájl jelszóval védett. |
| [getWarningCallback()](#getWarningCallback--) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Képviseli az opciókat, amelyek a Binary Large Objects (BLOB-ok) kezelési viselkedésének kezelésére használhatók, például ideiglenes fájlok használata vagy a maximális BLOB bájt memória. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Képviseli az opciókat, amelyek a Binary Large Objects (BLOB-ok) kezelési viselkedésének kezelésére használhatók, például ideiglenes fájlok használata vagy a maximális BLOB bájt memória. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Megadja a prezentáció által használandó külső betűtípusok forrásait. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Megadja a prezentáció által használandó külső betűtípusok forrásait. |
| [getInterruptionToken()](#getInterruptionToken--) | Az megszakítási kérések figyelésére szolgáló token. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Az megszakítási kérések figyelésére szolgáló token. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Visszaadja vagy beállítja a külső erőforrások betöltését kezelő visszahívási interfészt. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Visszaadja vagy beállítja a külső erőforrások betöltését kezelő visszahívási interfészt. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Lekéri a táblázatok opcióit. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Lekéri a táblázatok opcióit. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Megállapítja, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltése közben. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Megállapítja, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltése közben. |
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

**Visszatérési érték:**
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

Visszaadja vagy beállítja a Regular betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. Olvasás/írás String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Használja a betöltési beállításokat az alapértelmezett reguláris és ázsiai betűtípusok meghatározásához
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Töltse be a prezentációt
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Diakép (thumbnail) generálása
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
>      // PDF generálása
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS generálása
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatérési érték:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Visszaadja vagy beállítja a Regular betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. Olvasás/írás String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Használja a betöltési beállításokat az alapértelmezett reguláris és ázsiai betűtípusok meghatározásához
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Töltse be a prezentációt
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Diakép (thumbnail) generálása
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

Visszaadja vagy beállítja a Symbol betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Visszaadja vagy beállítja a Symbol betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Visszaadja vagy beállítja az Asian betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Visszaadja vagy beállítja az Asian betűtípust, amelyet akkor használ, ha a forrás betűtípust nem találja. Olvasás/írás String.

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
>  // munkáljon a dekódolt prezentációval
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Érték: A jelszó.

**Visszatérési érték:**
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
>  // munkáljon a dekódolt prezentációval
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

Ez a tulajdonság akkor érvényes, ha a prezentáció fájl jelszóval védett. A true érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni egy titkosított prezentációból, a jelszót figyelmen kívül hagyva. A false érték azt jelenti, hogy a teljes titkosított prezentációt a megfelelő jelszóval kell betölteni. Ha a prezentáció nincs titkosítva, a tulajdonság értéke mindig figyelmen kívül marad. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak és a tulajdonság értéke true, akkor a dokumentumtulajdonságok nem tölthetők be, és kivétel lesz dobva. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Ez a tulajdonság akkor érvényes, ha a prezentáció fájl jelszóval védett. A true érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni egy titkosított prezentációból, a jelszót figyelmen kívül hagyva. A false érték azt jelenti, hogy a teljes titkosított prezentációt a megfelelő jelszóval kell betölteni. Ha a prezentáció nincs titkosítva, a tulajdonság értéke mindig figyelmen kívül marad. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak és a tulajdonság értéke true, akkor a dokumentumtulajdonságok nem tölthetők be, és kivétel lesz dobva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Visszatérési érték:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Képviseli az opciókat, amelyek a Binary Large Objects (BLOB-ok) kezelési viselkedésének kezelésére használhatók, például ideiglenes fájlok használata vagy a maximális BLOB bájt memória. Ezek az opciók a legjobb teljesítmény/ memóriafelhasználás arány beállítását célozzák egy adott környezet vagy követelmény esetén.

--------------------

A Binary Large Object (BLOB) egy bináris adat, amely egyetlen egységként van tárolva – azaz a BLOB lehet audio, videó vagy maga a prezentáció.

**Visszatérési érték:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Képviseli az opciókat, amelyek a Binary Large Objects (BLOB-ok) kezelési viselkedésének kezelésére használhatók, például ideiglenes fájlok használata vagy a maximális BLOB bájt memória. Ezek az opciók a legjobb teljesítmény/ memóriafelhasználás arány beállítását célozzák egy adott környezet vagy követelmény esetén.

--------------------

A Binary Large Object (BLOB) egy bináris adat, amely egyetlen egységként van tárolva – azaz a BLOB lehet audio, videó vagy maga a prezentáció.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Megadja a prezentáció által használandó külső betűtípusok forrásait. Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztoznak más prezentációkkal.

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
>  //dolgozzon a prezentációval
>  //A CustomFont1, CustomFont2, valamint az assets\fonts és a global\fonts mappákból és azok almappáiból származó betűtípusok is elérhetők a prezentáció számára
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatérési érték:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Megadja a prezentáció által használandó külső betűtípusok forrásait. Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztoznak más prezentációkkal.

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
>  //dolgozzon a prezentációval
>  //A CustomFont1, CustomFont2, valamint az assets\fonts és a global\fonts mappákból és azok almappáiból származó betűtípusok is elérhetők a prezentáció számára
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

Az megszakítási kérések figyelésére szolgáló token.

--------------------

Ez a token kezeli a teljes [IPresentation](../../com.aspose.slides/ipresentation) példány életciklusát. Bármely hosszú ideig futó művelet, például a prezentáció betöltése vagy mentése, a [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) metódusának meghívásával lesz megszakítva.

**Visszatérési érték:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Az megszakítási kérések figyelésére szolgáló token.

--------------------

Ez a token kezeli a teljes [IPresentation](../../com.aspose.slides/ipresentation) példány életciklusát. Bármely hosszú ideig futó művelet, például a prezentáció betöltése vagy mentése, a [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) metódusának meghívásával lesz megszakítva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Visszaadja vagy beállítja a külső erőforrások betöltését kezelő visszahívási interfészt. Olvasás/írás [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Visszatérési érték:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Visszaadja vagy beállítja a külső erőforrások betöltését kezelő visszahívási interfészt. Olvasás/írás [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Lekéri a táblázatok opcióit. Például ezek az opciók befolyásolják a diagramok képleteinek kiszámítását.

**Visszatérési érték:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Lekéri a táblázatok opcióit. Például ezek az opciók befolyásolják a diagramok képleteinek kiszámítását.

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
>      // Új négyszögletű alakzat hozzáadása szöveggel
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Ellenőrizze az első szakasz nyelvét
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
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
>      // Új négyszögletű alakzat hozzáadása szöveggel
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Ellenőrizze az első szakasz nyelvét
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

Megállapítja, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltése közben.

A beágyazott bináris objektumok típusai:

Olvasás/írás boolean .

--------------------

> ```
> A következő példa megmutatja, hogyan töltsük be a prezentációt beágyazott bináris objektumok nélkül.
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

Alapértelmezett érték **false** .

**Visszatérési érték:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Megállapítja, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltése közben.

A beágyazott bináris objektumok típusai:

Olvasás/írás boolean .

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

Alapértelmezett érték **false** .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |