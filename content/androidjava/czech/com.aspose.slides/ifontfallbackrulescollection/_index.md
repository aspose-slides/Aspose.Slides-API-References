---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides pro Android pomocí Java API
description: Reprezentuje kolekci pravidel FontFallBack definovaných uživatelem
type: docs
url: /cs/com.aspose.slides/ifontfallbackrulescollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

Reprezentuje kolekci pravidel FontFallBack definovaných uživatelem
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá pravidlo na zadaném indexu. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Přidá nové pravidlo FallBack na konec kolekce. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Odstraní první výskyt konkrétního pravidla FallBack z kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```

Získá pravidlo na zadaném indexu. Pouze pro čtení [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Získání prázdné nebo předinicializované kolekce pravidel z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Přidání několika pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Získání objektu prvního pravidla v kolekci
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```

Přidá nové pravidlo FallBack na konec kolekce.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Získání prázdné nebo předinicializované kolekce pravidel z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Přidání nového pravidla do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Specifikované pravidlo pro přidání |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```

Odstraní první výskyt konkrétního pravidla FallBack z kolekce.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Získání prázdné nebo předinicializované kolekce pravidel z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Přidání několika pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Získání objektu prvního pravidla v kolekci
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Odstraňování 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Pravidlo, které se má odstranit z kolekce. |