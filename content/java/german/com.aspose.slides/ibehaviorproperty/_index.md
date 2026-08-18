---
title: IBehaviorProperty
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Eigenschaftstypen für Animationsverhalten dar.
type: docs
url: /de/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

Stellt Eigenschaftstypen für Animationsverhalten dar. Folgt der Liste von Eigenschaften aus https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx und https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValue()](#getValue--) | Wert der Eigenschaft |
| [isCustom()](#isCustom--) | Zeigt, ob diese Eigenschaft nicht zur vordefinierten Eigenschaftsliste in der Spezifikation gehört: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
### getValue() {#getValue--}
```
public abstract String getValue()
```

Wert der Eigenschaft

**Rückgabe:**
java.lang.String
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```

Zeigt, ob diese Eigenschaft nicht zur vordefinierten Eigenschaftsliste in der Spezifikation gehört: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Rückgabe:**
boolean