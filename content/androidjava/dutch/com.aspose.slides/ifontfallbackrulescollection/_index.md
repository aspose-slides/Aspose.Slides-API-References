---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een verzameling FontFallBack-regels, gedefinieerd door de gebruiker
type: docs
url: /nl/com.aspose.slides/ifontfallbackrulescollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

Vertegenwoordigt een verzameling FontFallBack-regels, gedefinieerd door de gebruiker
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt de regel op op de opgegeven index. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Voegt een nieuwe FallBack-regel toe aan het einde van de collectie. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Verwijdert het eerste voorkomen van een specifieke FallBack-regel uit de collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```


Haalt de regel op op de opgegeven index. Alleen-lezen [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Ophalen van een lege of voorgeïnitialiseerde regelsverzameling van FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Toevoegen van meerdere regels aan de verzameling
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Ophalen van het object van de eerste regel in de verzameling
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```


Voegt een nieuwe FallBack-regel toe aan het einde van de collectie.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Ophalen van een lege of vooraf geïnitialiseerde regelsverzameling van FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Toevoegen van een nieuwe regel aan de verzameling
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Gespecificeerde regel voor toevoegen |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```


Verwijdert het eerste voorkomen van een specifieke FallBack-regel uit de collectie.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Ophalen van een lege of vooraf geïnitialiseerde regelsverzameling van FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Toevoegen van meerdere regels aan de verzameling
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Ophalen van het object van de eerste regel in de verzameling
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Verwijderen 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | De regel die uit de collectie moet worden verwijderd. |