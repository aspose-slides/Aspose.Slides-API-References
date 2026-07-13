---
title: ILoadOptions
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Umožňuje specifikovat další možnosti (například formát nebo výchozí písmo) při načítání prezentace.
type: docs
url: /cs/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Umožňuje specifikovat další možnosti (například formát nebo výchozí písmo) při načítání prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Vrací nebo nastavuje formát prezentace, která má být načtena. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Vrací nebo nastavuje formát prezentace, která má být načtena. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Vrací nebo nastavuje regulární písmo použité v případě, že není nalezeno zdrojové písmo. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Vrací nebo nastavuje regulární písmo použité v případě, že není nalezeno zdrojové písmo. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Vrací nebo nastavuje symbolické písmo použité v případě, že není nalezeno zdrojové písmo. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Vrací nebo nastavuje symbolické písmo použité v případě, že není nalezeno zdrojové písmo. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Vrací nebo nastavuje asijské písmo použité v případě, že není nalezeno zdrojové písmo. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Vrací nebo nastavuje asijské písmo použité v případě, že není nalezeno zdrojové písmo. |
| [getPassword()](#getPassword--) | Získá nebo nastaví heslo. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Získá nebo nastaví heslo. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. |
| [getWarningCallback()](#getWarningCallback--) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Reprezentuje možnosti, které lze použít pro správu chování při manipulaci s velkými binárními objekty (BLOB), například použití dočasných souborů nebo maximální počet bajtů BLOB v paměti. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Reprezentuje možnosti, které lze použít pro správu chování při manipulaci s velkými binárními objekty (BLOB), například použití dočasných souborů nebo maximální počet bajtů BLOB v paměti. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Určuje zdroje externích písem, která mají být použita v prezentaci. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Určuje zdroje externích písem, která mají být použita v prezentaci. |
| [getInterruptionToken()](#getInterruptionToken--) | Token pro sledování požadavků na přerušení. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Token pro sledování požadavků na přerušení. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Reprezentuje možnosti, které lze použít k určení dodatečného chování tabulek. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Reprezentuje možnosti, které lze použít k určení dodatečného chování tabulek. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Vrací nebo nastavuje výchozí jazyk textu v prezentaci. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Vrací nebo nastavuje výchozí jazyk textu v prezentaci. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Určuje, zda Aspose.Slides při načítání prezentace odstraní všechny vložené binární objekty. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Určuje, zda Aspose.Slides při načítání prezentace odstraní všechny vložené binární objekty. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Vrací nebo nastavuje formát prezentace, která má být načtena. **Čtení/Zápis** [LoadFormat](../../com.aspose.slides/loadformat).

**Návratová hodnota:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Vrací nebo nastavuje formát prezentace, která má být načtena. **Čtení/Zápis** [LoadFormat](../../com.aspose.slides/loadformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Vrací nebo nastavuje regulární písmo použité v případě, že není nalezeno zdrojové písmo. **Čtení/Zápis** String.

**Návratová hodnota:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Vrací nebo nastavuje regulární písmo použité v případě, že není nalezeno zdrojové písmo. **Čtení/Zápis** String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Vrací nebo nastavuje symbolické písmo použité v případě, že není nalezeno zdrojové písmo. **Čtení/Zápis** String.

**Návratová hodnota:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Vrací nebo nastavuje symbolické písmo použité v případě, že není nalezeno zdrojové písmo. **Čtení/Zápis** String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Vrací nebo nastavuje asijské písmo použité v případě, že není nalezeno zdrojové písmo. **Čtení/Zápis** String.

**Návratová hodnota:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Vrací nebo nastavuje asijské písmo použité v případě, že není nalezeno zdrojové písmo. **Čtení/Zápis** String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Získá nebo nastaví heslo. **Čtení/Zápis** String.

Value: The password.

**Návratová hodnota:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Získá nebo nastaví heslo. **Čtení/Zápis** String.

Value: The password.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. Hodnota true znamená, že je nutné načíst pouze vlastnosti dokumentu z šifrovaného souboru prezentace a heslo má být ignorováno. Hodnota false znamená, že celá šifrovaná prezentace musí být načtena s použitím správného hesla. Pokud prezentace není šifrovaná, pak je hodnota vlastnosti vždy ignorována. Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné a hodnota vlastnosti je true, pak vlastnosti dokumentu nelze načíst a bude vyvolána výjimka. **Čtení/Zápis** boolean.

**Návratová hodnota:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. Hodnota true znamená, že je nutné načíst pouze vlastnosti dokumentu z šifrovaného souboru prezentace a heslo má být ignorováno. Hodnota false znamená, že celá šifrovaná prezentace musí být načtena s použitím správného hesla. Pokud prezentace není šifrovaná, pak je hodnota vlastnosti vždy ignorována. Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné a hodnota vlastnosti je true, pak vlastnosti dokumentu nelze načíst a bude vyvolána výjimka. **Čtení/Zápis** boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. **Čtení/Zápis** [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Návratová hodnota:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. **Čtení/Zápis** [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Reprezentuje možnosti, které lze použít pro správu chování při manipulaci s velkými binárními objekty (BLOB), například použití dočasných souborů nebo maximální počet bajtů BLOB v paměti. Tyto možnosti jsou určeny k nastavení nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky.

--------------------

Binární velký objekt (BLOB) je binární data uložená jako jediná entita – tj. BLOB může být audio, video nebo samotná prezentace.

**Návratová hodnota:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Reprezentuje možnosti, které lze použít pro správu chování při manipulaci s velkými binárními objekty (BLOB), například použití dočasných souborů nebo maximální počet bajtů BLOB v paměti. Tyto možnosti jsou určeny k nastavení nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky.

--------------------

Binární velký objekt (BLOB) je binární data uložená jako jediná entita – tj. BLOB může být audio, video nebo samotná prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Určuje zdroje externích písem, která mají být použita v prezentaci. Tato písma jsou k dispozici prezentaci po celou dobu jejího životního cyklu a nejsou sdílena s jinými prezentacemi.

**Návratová hodnota:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Určuje zdroje externích písem, která mají být použita v prezentaci. Tato písma jsou k dispozici prezentaci po celou dobu jejího životního cyklu a nejsou sdílena s jinými prezentacemi.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Token pro sledování požadavků na přerušení.

--------------------

Tento token spravuje celou životnost instance [IPresentation](../../com.aspose.slides/ipresentation). Jakákoli dlouho běžící operace, například načítání nebo ukládání prezentace, bude přerušena voláním metody [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) třídy [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Návratová hodnota:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Token pro sledování požadavků na přerušení.

--------------------

Tento token spravuje celou životnost instance [IPresentation](../../com.aspose.slides/ipresentation). Jakákoli dlouho běžící operace, například načítání nebo ukládání prezentace, bude přerušena voláním metody [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) třídy [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. **Čtení/Zápis** [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Návratová hodnota:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Vrací nebo nastavuje rozhraní zpětného volání, které spravuje načítání externích zdrojů. **Čtení/Zápis** [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Reprezentuje možnosti, které lze použít k určení dodatečného chování tabulek.

**Návratová hodnota:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Reprezentuje možnosti, které lze použít k určení dodatečného chování tabulek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Vrací nebo nastavuje výchozí jazyk textu v prezentaci. **Čtení/Zápis** String.

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


**Návratová hodnota:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

Vrací nebo nastavuje výchozí jazyk textu v prezentaci. **Čtení/Zápis** String.

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

Určuje, zda Aspose.Slides při načítání prezentace odstraní všechny vložené binární objekty.

Typy vložených binárních objektů:

 *  
 *  
 *  

**Čtení/Zápis** boolean.

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

**Návratová hodnota:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Určuje, zda Aspose.Slides při načítání prezentace odstraní všechny vložené binární objekty.

Typy vložených binárních objektů:

 *  
 *  
 *  

**Čtení/Zápis** boolean.

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