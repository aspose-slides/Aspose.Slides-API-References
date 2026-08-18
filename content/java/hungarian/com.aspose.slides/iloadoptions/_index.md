---
title: ILoadOptions
second_title: Aspose.Slides for Java API Referencia
description: Lehetővé teszi további beállítások, például formátum vagy alapértelmezett betűtípus megadását a prezentáció betöltésekor.
type: docs
url: /hu/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Lehetővé teszi további beállítások (például formátum vagy alapértelmezett betűtípus) megadását a prezentáció betöltésekor.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Visszaadja vagy beállítja a betölteni kívánt prezentáció formátumát. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Visszaadja vagy beállítja a betölteni kívánt prezentáció formátumát. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó szabályos betűtípust. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó szabályos betűtípust. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó szimbólum betűtípust. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó szimbólum betűtípust. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó ázsiai betűtípust. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó ázsiai betűtípust. |
| [getPassword()](#getPassword--) | Lekérdezi vagy beállítja a jelszót. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Lekérdezi vagy beállítja a jelszót. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Ez a tulajdonság akkor értelmezhető, ha a prezentáció fájl jelszóval védett. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Ez a tulajdonság akkor értelmezhető, ha a prezentáció fájl jelszóval védett. |
| [getWarningCallback()](#getWarningCallback--) | Visszaad egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakad-e. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Visszaad egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakad-e. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Olyan beállításokat reprezentál, amelyek a BLOB-ok (Binary Large Objects) kezelési viselkedését szabályozzák, például ideiglenes fájlok használatát vagy a memória-beli BLOB-ok maximális méretét. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Olyan beállításokat reprezentál, amelyek a BLOB-ok (Binary Large Objects) kezelési viselkedését szabályozzák, például ideiglenes fájlok használatát vagy a memória-beli BLOB-ok maximális méretét. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Megadja a külső betűtípusok forrását, amelyeket a prezentáció használ. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Megadja a külső betűtípusok forrását, amelyeket a prezentáció használ. |
| [getInterruptionToken()](#getInterruptionToken--) | Az a token, amely a megszakítási kérések figyelésére szolgál. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Az a token, amely a megszakítási kérések figyelésére szolgál. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Visszaadja vagy beállítja a külső erőforrások betöltését kezelő visszahívási interfészt. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Visszaadja vagy beállítja a külső erőforrások betöltését kezelő visszahívási interfészt. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Olyan beállításokat reprezentál, amelyek további táblázatkezelő viselkedést határoznak meg. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Olyan beállításokat reprezentál, amelyek további táblázatkezelő viselkedést határoznak meg. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltésekor. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltésekor. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Visszaadja vagy beállítja a betölteni kívánt prezentáció formátumát. Olvasás/írás [LoadFormat](../../com.aspose.slides/loadformat).

**Visszatérési érték:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Visszaadja vagy beállítja a betölteni kívánt prezentáció formátumát. Olvasás/írás [LoadFormat](../../com.aspose.slides/loadformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó szabályos betűtípust. Olvasás-írás String.

**Visszatérési érték:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó szabályos betűtípust. Olvasás-írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó szimbólum betűtípust. Olvasás-írás String.

**Visszatérési érték:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó szimbólum betűtípust. Olvasás-írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó ázsiai betűtípust. Olvasás-írás String.

**Visszatérési érték:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Visszaadja vagy beállítja a forrásbetűtípus nem található esetén használandó ázsiai betűtípust. Olvasás-írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Lekérdezi vagy beállítja a jelszót. Olvasás-írás String.

Érték: A jelszó.

**Visszatérési érték:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Lekérdezi vagy beállítja a jelszót. Olvasás-írás String.

Érték: A jelszó.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Ez a tulajdonság akkor értelmezhető, ha a prezentáció fájl jelszóval védett. Az igaz érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni a titkosított prezentációból, a jelszó figyelmen kívül lesz hagyva. A hamis érték azt jelenti, hogy a teljes titkosított prezentációt a megfelelő jelszó használatával kell betölteni. Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak és az érték igaz, akkor a dokumentumtulajdonságok nem tölthetők be, és kivétel keletkezik. Olvasás-írás boolean.

**Visszatérési érték:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Ez a tulajdonság akkor értelmezhető, ha a prezentáció fájl jelszóval védett. Az igaz érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni a titkosított prezentációból, a jelszó figyelmen kívül lesz hagyva. A hamis érték azt jelenti, hogy a teljes titkosított prezentációt a megfelelő jelszó használatával kell betölteni. Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak és az érték igaz, akkor a dokumentumtulajdonságok nem tölthetők be, és kivétel keletkezik. Olvasás-írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Visszaad egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakad-e. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Visszatérési érték:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Visszaad egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakad-e. Olvasás/írás [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Olyan beállításokat reprezentál, amelyek a BLOB-ok (Binary Large Objects) kezelési viselkedését szabályozzák, például ideiglenes fájlok használatát vagy a memória-beli BLOB-ok maximális méretét. Ezek a beállítások a legjobb teljesítmény-/memória-fogyasztási arány elérését célozzák meg egy adott környezetben vagy követelményrendszerben.

--------------------

A Binary Large Object (BLOB) egy bináris adat, amely egyetlen egységként van tárolva – például egy BLOB lehet hang, videó vagy a prezentáció maga.

**Visszatérési érték:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Olyan beállításokat reprezentál, amelyek a BLOB-ok (Binary Large Objects) kezelési viselkedését szabályozzák, például ideiglenes fájlok használatát vagy a memória-beli BLOB-ok maximális méretét. Ezek a beállítások a legjobb teljesítmény-/memória-fogyasztási arány elérését célozzák meg egy adott környezetben vagy követelményrendszerben.

--------------------

A Binary Large Object (BLOB) egy bináris adat, amely egyetlen egységként van tárolva – például egy BLOB lehet hang, videó vagy a prezentáció maga.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Megadja a külső betűtípusok forrását, amelyeket a prezentáció használ. Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztódnak meg más prezentációkkal.

**Visszatérési érték:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Megadja a külső betűtípusok forrását, amelyeket a prezentáció használ. Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztódnak meg más prezentációkkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Az a token, amely a megszakítási kérések figyelésére szolgál.

--------------------

Ez a token kezeli az egész [IPresentation](../../com.aspose.slides/ipresentation) példány életciklusát. Bármely hosszú ideig futó művelet, például a prezentáció betöltése vagy mentése, megszakítható a [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) metódus meghívásával a [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) objektumon.

**Visszatérési érték:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Az a token, amely a megszakítási kérések figyelésére szolgál.

--------------------

Ez a token kezeli az egész [IPresentation](../../com.aspose.slides/ipresentation) példány életciklusát. Bármely hosszú ideig futó művelet, például a prezentáció betöltése vagy mentése, megszakítható a [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) metódus meghívásával a [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) objektumon.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Visszaad egy visszahívási interfészt, amely a külső erőforrások betöltését kezeli. Olvasás/írás [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Visszatérési érték:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Visszaad egy visszahívási interfészt, amely a külső erőforrások betöltését kezeli. Olvasás/írás [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Olyan beállításokat reprezentál, amelyek további táblázatkezelő viselkedést definiálnak.

**Visszatérési érték:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Olyan beállításokat reprezentál, amelyek további táblázatkezelő viselkedést definiálnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
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
>  // Használja a betöltési beállításokat az alapértelmezett szövegnyelv meghatározásához
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
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltésekor.

A beágyazott bináris objektumok típusai:

 *  
 *  
 *  

Olvasás/írás boolean.

--------------------

> ```
> A következő példa bemutatja, hogyan töltsük be a prezentációt beágyazott bináris objektumok nélkül.
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

Az alapértelmezett érték **false**.

**Visszatérési érték:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltésekor.

A beágyazott bináris objektumok típusai:

 *  
 *  
 *  

Olvasás/írás boolean.

--------------------

> ```
> A következő példa bemutatja, hogyan töltsük be a prezentációt beágyazott bináris objektumok nélkül.
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

Az alapértelmezett érték **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |