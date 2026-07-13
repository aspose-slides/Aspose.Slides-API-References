---
title: LoadOptions
second_title: Aspose.Slides pro Android přes Java API Reference
description: Umožňuje specifikovat další možnosti, jako je formát nebo výchozí písmo při načítání prezentace.
type: docs
url: /cs/com.aspose.slides/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Umožňuje zadat další možnosti (např. formát nebo výchozí písmo) při načítání prezentace.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Vytvoří nové výchozí možnosti načítání. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Vytvoří nové možnosti načítání. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Vrací nebo nastavuje formát prezentace k načtení. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Vrací nebo nastavuje formát prezentace k načtení. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Vrací nebo nastavuje regularní písmo použité v případě, že výchozí písmo není nalezeno. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Vrací nebo nastavuje regularní písmo použité v případě, že výchozí písmo není nalezeno. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Vrací nebo nastavuje symbolové písmo použité v případě, že výchozí písmo není nalezeno. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Vrací nebo nastavuje symbolové písmo použité v případě, že výchozí písmo není nalezeno. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Vrací nebo nastavuje asijské písmo použité v případě, že výchozí písmo není nalezeno. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Vrací nebo nastavuje asijské písmo použité v případě, že výchozí písmo není nalezeno. |
| [getPassword()](#getPassword--) | Načítá nebo nastavuje heslo. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Načítá nebo nastavuje heslo. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. |
| [getWarningCallback()](#getWarningCallback--) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Reprezentuje možnosti, které lze použít k řízení chování při práci s Binary Large Objects (BLOBy), například používání dočasných souborů nebo maximální počet bajtů BLOBů v paměti. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Reprezentuje možnosti, které lze použít k řízení chování při práci s Binary Large Objects (BLOBy), například používání dočasných souborů nebo maximální počet bajtů BLOBů v paměti. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Specifikuje zdroje externích písem, které se mají použít v prezentaci. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Specifikuje zdroje externích písem, které se mají použít v prezentaci. |
| [getInterruptionToken()](#getInterruptionToken--) | Token pro sledování požadavků na přerušení. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Token pro sledování požadavků na přerušení. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Načítá možnosti pro tabulky. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Načítá možnosti pro tabulky. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Vrací nebo nastavuje výchozí jazyk textu prezentace. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Vrací nebo nastavuje výchozí jazyk textu prezentace. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Určuje, zda Aspose.Slides při načítání prezentace vymaže všechny vložené binární objekty. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Určuje, zda Aspose.Slides při načítání prezentace vymaže všechny vložené binární objekty. |
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
| loadFormat | int | Formát prezentace k načtení. |
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Vrací nebo nastavuje formát prezentace k načtení. Číst/Zapisovat [LoadFormat](../../com.aspose.slides/loadformat).

**Vrací:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Vrací nebo nastavuje formát prezentace k načtení. Číst/Zapisovat [LoadFormat](../../com.aspose.slides/loadformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Vrací nebo nastavuje regularní písmo použité v případě, že výchozí písmo není nalezeno. Číst/Zapisovat String.

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
>      // Vytvořit miniaturu snímku
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
>      // Vytvořit PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Vytvořit XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Vrací nebo nastavuje regularní písmo použité v případě, že výchozí písmo není nalezeno. Číst/Zapisovat String.

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
>      // Vytvořit miniaturu snímku
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
>      // Vytvořit PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Vytvořit XPS
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

Vrací nebo nastavuje symbolové písmo použité v případě, že výchozí písmo není nalezeno. Číst/Zapisovat String.

**Vrací:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Vrací nebo nastavuje symbolové písmo použité v případě, že výchozí písmo není nalezeno. Číst/Zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Vrací nebo nastavuje asijské písmo použité v případě, že výchozí písmo není nalezeno. Číst/Zapisovat String.

**Vrací:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Vrací nebo nastavuje asijské písmo použité v případě, že výchozí písmo není nalezeno. Číst/Zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public final String getPassword()
```

Načítá nebo nastavuje heslo. Číst/Zapisovat String.

--------------------

> ```
> Následující ukázkový kód ukazuje, jak otevřít chráněnou heslem prezentaci PowerPoint.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // pracujte s dešifrovanou prezentací
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Hodnota: Heslo.

**Vrací:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Načítá nebo nastavuje heslo. Číst/Zapisovat String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // pracujte s dešifrovanou prezentací
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

Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. Hodnota true znamená, že se z šifrovaného souboru načtou pouze vlastnosti dokumentu a heslo se ignoruje. Hodnota false znamená, že se načte celý šifrovaný soubor s použitím správného hesla. Pokud soubor není šifrován, hodnota vlastnosti se vždy ignoruje. Pokud nejsou vlastnosti dokumentu šifrovaného souboru veřejné a hodnota je true, nelze je načíst a bude vyvolána výjimka. Číst/Zapisovat boolean.

**Vrací:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public                                     
```

Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. Hodnota true znamená, že se z šifrovaného souboru načtou pouze vlastnosti dokumentu a heslo se ignoruje. Hodnota false znamená, že se načte celý šifrovaný soubor s použitím správného hesla. Pokud soubor není šifrován, hodnota vlastnosti se vždy ignoruje. Pokud nejsou vlastnosti dokumentu šifrovaného souboru veřejné a hodnota je true, nelze je načíst a bude vyvolána výjimka. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. Číst/Zapisovat [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Vrací:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. Číst/Zapisovat [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Reprezentuje možnosti, které lze použít k řízení chování při práci s Binary Large Objects (BLOBy), například používání dočasných souborů nebo maximální počet bajtů BLOBů v paměti. Tyto možnosti jsou určeny k nastavení nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky.

--------------------

Binární velký objekt (BLOB) je binární data uložená jako jedna entita – např. BLOB může být audio, video nebo samotná prezentace.

**Vrací:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Reprezentuje možnosti, které lze použít k řízení chování při práci s Binary Large Objects (BLOBy), například používání dočasných souborů nebo maximální počet bajtů BLOBů v paměti. Tyto možnosti jsou určeny k nastavení nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky.

--------------------

Binární velký objekt (BLOB) je binární data uložená jako jedna entita – např. BLOB může být audio, video nebo samotná prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Specifikuje zdroje externích písem, které se mají použít v prezentaci. Tato písma jsou pro prezentaci dostupná po celou dobu jejího životního cyklu a nejsou sdílena s jinými prezentacemi.

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
>  //pracujte s prezentací
>  //CustomFont1, CustomFont2 i fonty ze složek assets\fonts a global\fonts a jejich podsložek jsou k dispozici v prezentaci
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Vrací:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Specifikuje zdroje externích písem, které se mají použít v prezentaci. Tato písma jsou pro prezentaci dostupná po celou dobu jejího životního cyklu a nejsou sdílena s jinými prezentacemi.

--------------------

> ```
> Následující příklad ukazuje, jak zadat vlastní fonty používané v prezentaci PowerPoint.
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
>  //pracujte s prezentací
>  //CustomFont1, CustomFont2 i fonty ze složek assets\fonts a global\fonts a jejich podsložek jsou k dispozici v prezentaci
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

Tento token spravuje celou dobu životnosti instance [IPresentation](../../com.aspose.slides/ipresentation). Jakákoli dlouho běžící operace, například načítání nebo ukládání prezentace, bude přerušena voláním metody [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) objektu [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Vrací:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Token pro sledování požadavků na přerušení.

--------------------

Tento token spravuje celou dobu životnosti instance [IPresentation](../../com.aspose.slides/ipresentation). Jakákoli dlouho běžící operace, například načítání nebo ukládání prezentace, bude přerušena voláním metody [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) objektu [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |
### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. Číst/Zapisovat [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Vrací:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. Číst/Zapisovat [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |
### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Načítá možnosti pro tabulky. Například tyto možnosti ovlivňují výpočet vzorců pro grafy.

**Vrací:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Načítá možnosti pro tabulky. Například tyto možnosti ovlivňují výpočet vzorců pro grafy.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |
### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Vrací nebo nastavuje výchozí jazyk textu prezentace. Číst/Zapisovat String.

--------------------

> ```
> Example:
>   
>  // Použijte možnosti načítání k určení výchozího jazyka textu
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


**Vrací:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Vrací nebo nastavuje výchozí jazyk textu prezentace. Číst/Zapisovat String.

--------------------

> ```
> Example:
>   
>  // Použijte možnosti načítání k určení výchozího jazyka textu
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

Určuje, zda Aspose.Slides vymaže všechny vložené binární objekty při načítání prezentace.

Typy vložených binárních objektů:

Číst/Zapisovat boolean.

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

**Vrací:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Určuje, zda Aspose.Slides vymaže všechny vložené binární objekty při načítání prezentace.

Typy vložených binárních objektů:

Číst/Zapisovat boolean.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |