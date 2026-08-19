---
title: ILoadOptions
second_title: Aspose.Slides for Java API Reference
description: Umožňuje zadat další možnosti, jako je formát nebo výchozí písmo při načítání prezentace.
type: docs
url: /cs/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Umožňuje zadat další možnosti (jako je formát nebo výchozí písmo) při načítání prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Vrací nebo nastavuje formát prezentace k načtení. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Vrací nebo nastavuje formát prezentace k načtení. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Vrací nebo nastavuje výchozí regulární písmo použité v případě, že není nalezeno zdrojové písmo. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Vrací nebo nastavuje výchozí regulární písmo použité v případě, že není nalezeno zdrojové písmo. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Vrací nebo nastavuje výchozí symbolové písmo použité v případě, že není nalezeno zdrojové písmo. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Vrací nebo nastavuje výchozí symbolové písmo použité v případě, že není nalezeno zdrojové písmo. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Vrací nebo nastavuje výchozí asijské písmo použité v případě, že není nalezeno zdrojové písmo. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Vrací nebo nastavuje výchozí asijské písmo použité v případě, že není nalezeno zdrojové písmo. |
| [getPassword()](#getPassword--) | Získá nebo nastaví heslo. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Získá nebo nastaví heslo. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. |
| [getWarningCallback()](#getWarningCallback--) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Reprezentuje možnosti, které lze použít k řízení chování při zpracování Binary Large Objects (BLOBs), například používání dočasných souborů nebo maximální počet bajtů BLOBs v paměti. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Reprezentuje možnosti, které lze použít k řízení chování při zpracování Binary Large Objects (BLOBs), například používání dočasných souborů nebo maximální počet bajtů BLOBs v paměti. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Určuje zdroje externích písem, které mají být použity v prezentaci. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Určuje zdroje externích písem, které mají být použity v prezentaci. |
| [getInterruptionToken()](#getInterruptionToken--) | Token k sledování požadavků na přerušení. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Token k sledování požadavků na přerušení. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Reprezentuje možnosti, které lze použít k určení dalšího chování tabulek. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Reprezentuje možnosti, které lze použít k určení dalšího chování tabulek. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Vrací nebo nastavuje výchozí jazyk textu prezentace. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Vrací nebo nastavuje výchozí jazyk textu prezentace. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Určuje, zda Aspose.Slides smaže všechny vložené binární objekty při načítání prezentace. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Určuje, zda Aspose.Slides smaže všechny vložené binární objekty při načítání prezentace. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


Vrací nebo nastavuje formát prezentace k načtení. Číst/zapisovat [LoadFormat](../../com.aspose.slides/loadformat).

**Vrací:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```


Vrací nebo nastavuje formát prezentace k načtení. Číst/zapisovat [LoadFormat](../../com.aspose.slides/loadformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


Vrací nebo nastavuje výchozí regulární písmo použité v případě, že není nalezeno zdrojové písmo. Číst/zapisovat String.

**Vrací:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


Vrací nebo nastavuje výchozí regulární písmo použité v případě, že není nalezeno zdrojové písmo. Číst/zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```


Vrací nebo nastavuje výchozí symbolové písmo použité v případě, že není nalezeno zdrojové písmo. Číst/zapisovat String.

**Vrací:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```


Vrací nebo nastavuje výchozí symbolové písmo použité v případě, že není nalezeno zdrojové písmo. Číst/zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```


Vrací nebo nastavuje výchozí asijské písmo použité v případě, že není nalezeno zdrojové písmo. Číst/zapisovat String.

**Vrací:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```


Vrací nebo nastavuje výchozí asijské písmo použité v případě, že není nalezeno zdrojové písmo. Číst/zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Získá nebo nastaví heslo. Číst/zapisovat String.

Hodnota: Heslo.

**Vrací:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```


Získá nebo nastaví heslo. Číst/zapisovat String.

Hodnota: Heslo.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```


Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. Hodnota **true** znamená, že z šifrovaného souboru mají být načteny pouze vlastnosti dokumentu a heslo se má ignorovat. Hodnota **false** znamená, že celý šifrovaný soubor se načte s použitím správného hesla. Pokud prezentace není šifrována, tato hodnota se vždy ignoruje. Pokud nejsou veřejné vlastnosti šifrovaného souboru a hodnota je **true**, vlastnosti nelze načíst a bude vyvolána výjimka. Číst/zapisovat boolean.

**Vrací:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```


Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. Hodnota **true** znamená, že z šifrovaného souboru mají být načteny pouze vlastnosti dokumentu a heslo se má ignorovat. Hodnota **false** znamená, že celý šifrovaný soubor se načte s použitím správného hesla. Pokud prezentace není šifrována, tato hodnota se vždy ignoruje. Pokud nejsou veřejné vlastnosti šifrovaného souboru a hodnota je **true**, vlastnosti nelze načíst a bude vyvolána výjimka. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. Číst/zapisovat [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Vrací:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. Číst/zapisovat [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```


Reprezentuje možnosti, které lze použít k řízení chování při zpracování Binary Large Objects (BLOBs), například používání dočasných souborů nebo maximální počet bajtů BLOBs v paměti. Tyto možnosti jsou určeny k nastavení nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky.

--------------------

Binary Large Object (BLOB) je binární data uložená jako jediná entita – např. BLOB může být audio, video nebo samotná prezentace.

**Vrací:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```


Reprezentuje možnosti, které lze použít k řízení chování při zpracování Binary Large Objects (BLOBs), například používání dočasných souborů nebo maximální počet bajtů BLOBs v paměti. Tyto možnosti jsou určeny k nastavení nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky.

--------------------

Binary Large Object (BLOB) je binární data uložená jako jediná entita – např. BLOB může být audio, video nebo samotná prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```


Určuje zdroje externích písem, které mají být použity v prezentaci. Tato písma jsou k dispozici prezentaci po celou její životnost a nejsou sdílena s jinými prezentacemi.

**Vrací:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```


Určuje zdroje externích písem, které mají být použity v prezentaci. Tato písma jsou k dispozici prezentaci po celou její životnost a nejsou sdílena s jinými prezentacemi.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```


Token k sledování požadavků na přerušení.

--------------------

Tento token spravuje celou životnost instance [IPresentation](../../com.aspose.slides/ipresentation). Jakákoli dlouho běžící operace, např. načítání nebo ukládání prezentace, bude přerušena voláním metody [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) třídy [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Vrací:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```


Token k sledování požadavků na přerušení.

--------------------

Tento token spravuje celou životnost instance [IPresentation](../../com.aspose.slides/ipresentation). Jakákoli dlouho běžící operace, např. načítání nebo ukládání prezentace, bude přerušena voláním metody [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) třídy [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```


Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. Číst/zapisovat [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Vrací:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```


Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. Číst/zapisovat [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```


Reprezentuje možnosti, které lze použít k určení dalšího chování tabulek.

**Vrací:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```


Reprezentuje možnosti, které lze použít k určení dalšího chování tabulek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```


Vrací nebo nastavuje výchozí jazyk textu prezentace. Číst/zapisovat String.

--------------------

> ```
> Example:
>   
>  // Use load options to define the default text culture
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Add new rectangle shape with text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Check the first portion language
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```


Vrací nebo nastavuje výchozí jazyk textu prezentace. Číst/zapisovat String.

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
public abstract boolean getDeleteEmbeddedBinaryObjects()
```


Určuje, zda Aspose.Slides smaže všechny vložené binární objekty při načítání prezentace.

Typy vložených binárních objektů:

 *  
 *  
 *  

Číst/zapisovat boolean .

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

Výchozí je **false** .

**Vrací:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```


Určuje, zda Aspose.Slides smaže všechny vložené binární objekty při načítání prezentace.

Typy vložených binárních objektů:

 *  
 *  
 *  

Číst/zapisovat boolean .

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

Výchozí je **false** .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |