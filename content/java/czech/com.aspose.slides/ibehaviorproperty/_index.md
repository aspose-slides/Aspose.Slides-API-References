---
title: IBehaviorProperty
second_title: Aspose.Slides for Java API Reference
description: Represent property types for animation behavior.
type: docs
url: /cs/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

Reprezentuje typy vlastností pro animační chování. Následuje seznam vlastností z https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx a https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Metody

| Metoda | Popis |
| --- | --- |
| [getValue()](#getValue--) | Hodnota vlastnosti |
| [isCustom()](#isCustom--) | Ukazuje, zda tato vlastnost nepatří do seznamu předdefinovaných vlastností ve specifikaci: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
### getValue() {#getValue--}
```
public abstract String getValue()
```


Hodnota vlastnosti

**Vrací:**
java.lang.String
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Ukazuje, zda tato vlastnost nepatří do seznamu předdefinovaných vlastností ve specifikaci: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Vrací:**
boolean