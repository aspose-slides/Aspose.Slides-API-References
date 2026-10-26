---
title: LoadOptions
second_title: Aspose.Slides pro Java API Reference
description: Umožňuje zadat další možnosti, jako je formát nebo výchozí písmo při načítání prezentace.
type: docs
url: /cs/com.aspose.slides/loadoptions/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Umožňuje specifikovat další možnosti (např. formát nebo výchozí písmo) při načítání prezentace.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Vytvoří nové výchozí možnosti načítání. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Vytvoří nové možnosti načítání. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Vrací nebo nastavuje formát prezentace, která se má načíst. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Vrací nebo nastavuje formát prezentace, která se má načíst. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Vrací nebo nastavuje regulární písmo, které se použije, pokud není nalezeno zdrojové písmo. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Vrací nebo nastavuje regulární písmo, které se použije, pokud není nalezeno zdrojové písmo. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Vrací nebo nastavuje Symbol font použité v případě, že není nalezen zdrojový font. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Vrací nebo nastavuje Symbol font použité v případě, že není nalezen zdrojový font. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Vrací nebo nastavuje Asijské písmo použité v případě, že není nalezen zdrojový font. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Vrací nebo nastavuje Asijské písmo použité v případě, že není nalezen zdrojový font. |
| [getPassword()](#getPassword--) | Získá nebo nastaví heslo. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Získá nebo nastaví heslo. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. |
| [getWarningCallback()](#getWarningCallback--) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Reprezentuje možnosti, které lze použít k řízení chování manipulace s Binary Large Objects (BLOBs), například použití dočasných souborů nebo maximální velikost BLOB v paměti. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Reprezentuje možnosti, které lze použít k řízení chování manipulace s Binary Large Objects (BLOBs), například použití dočasných souborů nebo maximální velikost BLOB v paměti. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Určuje zdroje pro externí písma, která mají být použita v prezentaci. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Určuje zdroje pro externí písma, která mají být použita v prezentaci. |
| [getInterruptionToken()](#getInterruptionToken--) | Token pro sledování požadavků na přerušení. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Token pro sledování požadavků na přerušení. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Získá možnosti pro tabulkové kalkulace. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Získá možnosti pro tabulkové kalkulace. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Vrací nebo nastavuje výchozí jazyk pro text prezentace. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Vrací nebo nastavuje výchozí jazyk pro text prezentace. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Určuje, zda Aspose.Slides při načítání prezentace smaže všechny vložené binární objekty. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Určuje, zda Aspose.Slides při načítání prezentace smaže všechny vložené binární objekty. |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Vytvoří nové výchozí možnosti načítání.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Vytvoří nové možnosti načítání.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| loadFormat | int | Formát prezentace, která se má načíst. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Vrací nebo nastavuje formát prezentace, která se má načíst. Čtení/zápis [LoadFormat](../../com.aspose.slides/loadformat).

**Vrácená hodnota:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Vrací nebo nastavuje formát prezentace, která se má načíst. Čtení/zápis [LoadFormat](../../com.aspose.slides/loadformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Vrací nebo nastavuje regulární písmo, které se použije, pokud není nalezeno zdrojové písmo. Čtení/zápis String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Použijte možnosti načítání k definování výchozího regulárního a asijského písma
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Načíst prezentaci
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Vygenerovat miniaturu snímku
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Vygenerovat PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Vygenerovat XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrácená hodnota:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Vrací nebo nastavuje regulární písmo, které se použije, pokud není nalezeno zdrojové písmo. Čtení/zápis String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Použijte možnosti načítání k definování výchozího regulárního a asijského písma
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Načíst prezentaci
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Vygenerovat miniaturu snímku
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Vygenerovat PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Vygenerovat XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Vrací nebo nastavuje Symbol font použité v případě, že není nalezen zdrojový font. Čtení/zápis String.

**Vrácená hodnota:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Vrací nebo nastavuje Symbol font použité v případě, že není nalezen zdrojový font. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Vrací nebo nastavuje Asijské písmo použité v případě, že není nalezen zdrojový font. Čtení/zápis String.

**Vrácená hodnota:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Vrací nebo nastavuje Asijské písmo použité v případě, že není nalezen zdrojový font. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Získá nebo nastaví heslo. Čtení/zápis String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // práce s dešifrovanou prezentací
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Hodnota: Heslo.

**Vrácená hodnota:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Získá nebo nastaví heslo. Čtení/zápis String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // práce s dešifrovanou prezentací
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Hodnota: Heslo.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. Hodnota **true** znamená, že se mají načíst pouze vlastnosti dokumentu z šifrovaného souboru a heslo se má ignorovat. Hodnota **false** znamená, že se má načíst celá šifrovaná prezentace s použitím správného hesla. Pokud prezentace není šifrovaná, hodnota vlastnosti je vždy ignorována. Pokud nejsou vlastnosti dokumentu šifrovaného souboru veřejné a hodnota je **true**, vlastnosti dokumentu nelze načíst a bude vyvolána výjimka. Čtení/zápis boolean.

**Vrácená hodnota:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. Hodnota **true** znamená, že se mají načíst pouze vlastnosti dokumentu z šifrovaného souboru a heslo se má ignorovat. Hodnota **false** znamená, že se má načíst celá šifrovaná prezentace s použitím správného hesla. Pokud prezentace není šifrovaná, hodnota vlastnosti je vždy ignorována. Pokud nejsou vlastnosti dokumentu šifrovaného souboru veřejné a hodnota je **true**, vlastnosti dokumentu nelze načíst a bude vyvolána výjimka. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Čtení/zápis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Vrácená hodnota:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Čtení/zápis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Reprezentuje možnosti, které lze použít k řízení chování manipulace s Binary Large Objects (BLOBs), například použití dočasných souborů nebo maximální velikost BLOB v paměti. Tyto možnosti jsou určeny k nastavení nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky.

--------------------

Binary Large Object (BLOB) je binární data uložená jako jedinečná entita – tj. BLOB může být audio, video nebo samotná prezentace.

**Vrácená hodnota:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Reprezentuje možnosti, které lze použít k řízení chování manipulace s Binary Large Objects (BLOBs), například použití dočasných souborů nebo maximální velikost BLOB v paměti. Tyto možnosti jsou určeny k nastavení nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky.

--------------------

Binary Large Object (BLOB) je binární data uložená jako jedinečná entita – tj. BLOB může být audio, video nebo samotná prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Určuje zdroje pro externí písma, která mají být použita v prezentaci. Tato písma jsou k dispozici během celého životního cyklu prezentace a nejsou sdílena s jinými prezentacemi.

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
>  //pracujte s prezentací
>  //CustomFont1, CustomFont2 stejně jako písma z složek assets\fonts a global\fonts a jejich podadresářů jsou k dispozici prezentaci
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Vrácená hodnota:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Určuje zdroje pro externí písma, která mají být použita v prezentaci. Tato písma jsou k dispozici během celého životního cyklu prezentace a nejsou sdílena s jinými prezentacemi.

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
>  //pracujte s prezentací
>  //CustomFont1, CustomFont2 stejně jako písma ze složek assets\fonts a global\fonts a jejich podadresářů jsou k dispozici prezentaci
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Token pro sledování požadavků na přerušení.

--------------------

Tento token spravuje celou životnost instance [IPresentation](../../com.aspose.slides/ipresentation). Každá dlouho běžící operace, například načítání nebo ukládání prezentace, bude přerušena voláním metody [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) instance [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Vrácená hodnota:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Token pro sledování požadavků na přerušení.

--------------------

Tento token spravuje celou životnost instance [IPresentation](../../com.aspose.slides/ipresentation). Každá dlouho běžící operace, například načítání nebo ukládání prezentace, bude přerušena voláním metody [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) instance [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. Čtení/zápis [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Vrácená hodnota:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. Čtení/zápis [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Získá možnosti pro tabulkové kalkulace. Například tyto možnosti ovlivňují výpočet vzorců pro grafy.

**Vrácená hodnota:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Získá možnosti pro tabulkové kalkulace. Například tyto možnosti ovlivňují výpočet vzorců pro grafy.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Vrací nebo nastavuje výchozí jazyk pro text prezentace. Čtení/zápis String.

--------------------

> ```
> Example:
>   
>  // Použijte možnosti načítání k definování výchozí kultury textu
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Přidejte nový obdélníkový tvar s textem
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Zkontrolujte jazyk první části
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrácená hodnota:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Vrací nebo nastavuje výchozí jazyk pro text prezentace. Čtení/zápis String.

--------------------

> ```
> Example:
>   
>  // Použijte možnosti načítání k definování výchozí kultury textu
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Přidejte nový obdélníkový tvar s textem
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Zkontrolujte jazyk první části
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Určuje, zda Aspose.Slides při načítání prezentace smaže všechny vložené binární objekty.

Typy vložených binárních objektů:

Čtení/zápis  boolean .

--------------------

> ```
> Následující příklad ukazuje, jak načíst prezentaci bez jakýchkoli vložených binárních objektů.
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

Výchozí hodnota je **false**.

**Vrácená hodnota:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Určuje, zda Aspose.Slides při načítání prezentace smaže všechny vložené binární objekty.

Typy vložených binárních objektů:

Čtení/zápis  boolean .

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

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |