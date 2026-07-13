---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides för Android via Java API-referensen
description: Representerar en samling av FontFallBack-regler som definieras av användaren
type: docs
url: /sv/com.aspose.slides/ifontfallbackrulescollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

Representerar en samling av FontFallBack-regler, definierade av användaren
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar regeln på det angivna indexet. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Lägg till en ny FallBack-regel i slutet av samlingen. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Tar bort den första förekomsten av en specifik FallBack-regel från samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```


Hämtar regeln på det angivna indexet. Skrivskyddad [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Hämtar en tom eller förinitierad reglerkollektion från FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Lägger till flera regler i kollektionen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Hämtar objektet för den första regeln i kollektionen
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```


Lägg till en ny FallBack-regel i slutet av samlingen.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Hämtar en tom eller förinitierad reglerkollektion från FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Lägger till en ny regel i kollektionen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Angiven regel för att lägga till |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```


Tar bort den första förekomsten av en specifik FallBack-regel från samlingen.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Hämtar en tom eller förinitierad reglerkollektion från FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Lägger till flera regler i kollektionen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Hämtar objektet för den första regeln i kollektionen
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Tar bort 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Regelen som ska tas bort från samlingen. |