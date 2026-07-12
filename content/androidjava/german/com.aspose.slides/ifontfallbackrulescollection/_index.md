---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von FontFallBack-Regeln dar, die vom Benutzer definiert wurden.
type: docs
url: /de/com.aspose.slides/ifontfallbackrulescollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

Stellt eine Sammlung von FontFallBack-Regeln dar, die vom Benutzer definiert wurden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt die Regel am angegebenen Index zurück. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Fügt eine neue FallBack-Regel am Ende der Sammlung hinzu. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Entfernt das erste Vorkommen einer bestimmten FallBack-Regel aus der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```


Gibt die Regel am angegebenen Index zurück. Nur lesbar [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Abrufen einer leeren oder vorkonfigurierten Regelsammlung vom FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Hinzufügen mehrerer Regeln zur Sammlung
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Abrufen des Objekts der ersten Regel in der Sammlung
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```


Fügt eine neue FallBack-Regel am Ende der Sammlung hinzu.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Abrufen einer leeren oder vorkonfigurierten Regelsammlung vom FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Hinzufügen einer neuen Regel zur Sammlung
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Angegebene Regel zum Hinzufügen |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```


Entfernt das erste Vorkommen einer bestimmten FallBack-Regel aus der Sammlung.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Abrufen einer leeren oder vorkonfigurierten Regelsammlung vom FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Hinzufügen mehrerer Regeln zur Sammlung
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Abrufen des Objekts der ersten Regel in der Sammlung
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Entfernen
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Die zu entfernende Regel aus der Sammlung. |