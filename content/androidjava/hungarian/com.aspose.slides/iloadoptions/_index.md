---
title: ILoadOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi további beállítások megadását, például formátum vagy alapértelmezett betűtípus, a bemutató betöltésekor.
type: docs
url: /hu/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Lehetővé teszi további beállítások (például formátum vagy alapértelmezett betűtípus) megadását a bemutató betöltésekor.
## Methods

| Method | Description |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Visszaadja vagy beállítja a betöltendő bemutató formátumát. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Visszaadja vagy beállítja a betöltendő bemutató formátumát. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Visszaadja vagy beállítja a forrás betűtípus hiányában használt normál betűtípust. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Visszaadja vagy beállítja a forrás betűtípusa nem található esetén használt normál betűtípust. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Visszaadja vagy beállítja a forrás betűtípusa nem található esetén használt szimbólum betűtípust. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Visszaadja vagy beállítja a forrás betűtípusa nem található esetén használt szimbólum betűtípust. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Visszaadja vagy beállítja a forrás betűtípusa nem található esetén használt ázsiai betűtípust. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Visszaadja vagy beállítja a forrás betűtípusa nem található esetén használt ázsiai betűtípust. |
| [getPassword()](#getPassword--) | Lekéri vagy beállítja a jelszót. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Lekéri vagy beállítja a jelszót. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Ez a tulajdonság akkor értelmes, ha a bemutató fájl jelszóval védett. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Ez a tulajdonság akkor értelmes, ha a bemutató fájl jelszóval védett. |
| [getWarningCallback()](#getWarningCallback--) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Képviseli azokat a beállításokat, amelyek a BLOB-ok (Binary Large Objects) kezelési viselkedésének irányítására használhatók, például ideiglenes fájlok használata vagy a memóriában legfeljebb ennyi BLOB bájt. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Képviseli azokat a beállításokat, amelyek a BLOB-ok (Binary Large Objects) kezelési viselkedésének irányítására használhatók, például ideiglenes fájlok használata vagy a memóriában legfeljebb ennyi BLOB bájt. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Megadja a prezentáció által használandó külső betűtípusok forrásait. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Megadja a prezentáció által használandó külső betűtípusok forrásait. |
| [getInterruptionToken()](#getInterruptionToken--) | A token, amely a megszakítási kérelmek figyelésére szolgál. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | A token, amely a megszakítási kérelmek figyelésére szolgál. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Visszaadja vagy beállítja a külső erőforrások betöltését kezelő visszahívási interfészt. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Visszaadja vagy beállítja a külső erőforrások betöltését kezelő visszahívási interfészt. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Képviseli azokat a beállításokat, amelyek további táblázatok viselkedését határozzák meg. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Képviseli azokat a beállításokat, amelyek további táblázatok viselkedését határozzák meg. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Meghatározza, hogy az Aspose.Slides töröl-e minden beágyazott bináris objektumot a prezentáció betöltése közben. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Meghatározza, hogy az Aspose.Slides töröl-e minden beágyazott bináris objektumot a prezentáció betöltése közben. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Visszaadja vagy beállítja a betöltendő bemutató formátumát. Olvasás/írás [LoadFormat](../../com.aspose.slides/loadformat).

**Visszatérési érték:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Visszaadja vagy beállítja a betöltendő bemutató formátumát. Olvasás/írás [LoadFormat](../../com.aspose.slides/loadformat).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Visszaadja vagy beállítja a forrás betűtípus hiányában használt normál betűtípust. Olvasás-írás String.

**Visszatérési érték:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Visszaadja vagy beállítja a forrás betűtípus hiányában használt normál betűtípust. Olvasás-írás String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Visszaadja vagy beállítja a forrás betűtípusa nem található esetén használt szimbólum betűtípust. Olvasás-írás String.

**Visszatérési érték:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Visszaadja vagy beállítja a forrás betűtípusa nem található esetén használt szimbólum betűtípust. Olvasás-írás String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Visszaadja vagy beállítja a forrás betűtípusa nem található esetén használt ázsiai betűtípust. Olvasás-írás String.

**Visszatérési érték:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Visszaadja vagy beállítja a forrás betűtípusa nem található esetén használt ázsiai betűtípust. Olvasás-írás String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Lekéri vagy beállítja a jelszót. Olvasás-írás String.

Érték: A jelszó.

**Visszatérési érték:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Lekéri vagy beállítja a jelszót. Olvasás-írás String.

Érték: A jelszó.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Ez a tulajdonság akkor értelmes, ha a bemutató fájl jelszóval védett. A true érték azt jelenti, hogy csak a dokumentumtulajdonságokat kell betölteni a titkosított bemutatóból, a jelszót figyelmen kívül hagyva. A false érték azt jelenti, hogy a teljes titkosított bemutatót a megfelelő jelszóval kell betölteni. Ha a bemutató nincs titkosítva, akkor a tulajdonságérték mindig figyelmen kívül van hagyva. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak, és a tulajdonság értéke true, akkor a dokumentumtulajdonságok nem tölthetők be, és kivétel keletkezik. Olvasás-írás boolean.

**Visszatérési érték:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Ez a tulajdonság akkor értelmes, ha a bemutató fájl jelszóval védett. A true érték azt jelenti, hogy csak a dokumentumtulajdonságokat kell betölteni a titkosított bemutatóból, a jelszót figyelmen kívül hagyva. A false érték azt jelenti, hogy a teljes titkosított bemutatót a megfelelő jelszóval kell betölteni. Ha a bemutató nincs titkosítva, akkor a tulajdonságérték mindig figyelmen kívül van hagyva. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak, és a tulajdonság értéke true, akkor a dokumentumtulajdonságok nem tölthetők be, és kivétel keletkezik. Olvasás-írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Visszatérési érték:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Képviseli azokat a beállításokat, amelyek a Binary Large Objects (BLOB-ok) kezelésének viselkedését szabályozzák, például ideiglenes fájlok használata vagy a memóriában legfeljebb ennyi BLOB bájt. Ezek a beállítások a legjobb teljesítmény-memória fogyasztási arány elérését célozzák egy adott környezetben vagy követelmény esetén.

--------------------

A Binary Large Object (BLOB) egy bináris adat, amely egyetlen entitásként van tárolva – például a BLOB egy hang, videó vagy maga a bemutató is lehet.

**Visszatérési érték:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Képviseli azokat a beállításokat, amelyek a Binary Large Objects (BLOB-ok) kezelésének viselkedését szabályozzák, például ideiglenes fájlok használata vagy a memóriában legfeljebb ennyi BLOB bájt. Ezek a beállítások a legjobb teljesítmény-memória fogyasztási arány elérését célozzák egy adott környezetben vagy követelmény esetén.

--------------------

A Binary Large Object (BLOB) egy bináris adat, amely egyetlen entitásként van tárolva – például a BLOB egy hang, videó vagy maga a bemutató is lehet.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Megadja a prezentáció által használandó külső betűtípusok forrásait. Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztottak más prezentációkkal.

**Visszatérési érték:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Megadja a prezentáció által használandó külső betűtípusok forrásait. Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztottak más prezentációkkal.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

A token, amely a megszakítási kérések figyelésére szolgál.

--------------------

Ez a token kezeli a teljes [IPresentation](../../com.aspose.slides/ipresentation) példány életciklusát. Bármely hosszú művelet, például a bemutató betöltése vagy mentése, a [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) metódus meghívásával lesz megszakítva a [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Visszatérési érték:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

A token, amely a megszakítási kérések figyelésére szolgál.

--------------------

Ez a token kezeli a teljes [IPresentation](../../com.aspose.slides/ipresentation) példány életciklusát. Bármely hosszú művelet, például a bemutató betöltése vagy mentése, a [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) metódus meghívásával lesz megszakítva a [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Visszaadja vagy beállítja a külső erőforrások betöltését kezelő visszahívási interfészt. Olvasás/írás [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Visszatérési érték:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Visszaadja vagy beállítja a külső erőforrások betöltését kezelő visszahívási interfészt. Olvasás/írás [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Képviseli azokat a beállításokat, amelyek további táblázatok viselkedését specifikálják.

**Visszatérési érték:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Képviseli azokat a beállításokat, amelyek további táblázatok viselkedését specifikálják.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. Olvasás/írás String.

--------------------

> ```
> Example:
>   
>  // Használja a load options-t az alapértelmezett szövegkultúra meghatározásához
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


**Visszatérési érték:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. Olvasás/írás String.

--------------------

> ```
> Example:
>   
>  // Használja a load options-t az alapértelmezett szövegkultúra meghatározásához
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Meghatározza, hogy az Aspose.Slides töröl-e minden beágyazott bináris objektumot a prezentáció betöltése közben.

A beágyazott bináris objektumok típusai:

 *  
 *  
 *  

Olvasás/írás boolean.

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

Alapértelmezett érték **false**.

**Visszatérési érték:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Meghatározza, hogy az Aspose.Slides töröl-e minden beágyazott bináris objektumot a prezentáció betöltése közben.

A beágyazott bináris objektumok típusai:

 *  
 *  
 *  

Olvasás/írás boolean.

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

Alapértelmezett érték **false**.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |