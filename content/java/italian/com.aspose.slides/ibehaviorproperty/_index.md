---
title: IBehaviorProperty
second_title: Aspose.Slides for Java API Reference
description: Rappresenta i tipi di proprietà per il comportamento dell'animazione.
type: docs
url: /it/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

Rappresenta i tipi di proprietà per il comportamento dell'animazione. Follows the list of properties from https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx and https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValue()](#getValue--) | Valore della proprietà |
| [isCustom()](#isCustom--) | Mostra se questa proprietà non appartiene all'elenco delle proprietà predefinite nella specifica: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
### getValue() {#getValue--}
```
public abstract String getValue()
```


Valore della proprietà

**Restituisce:**
java.lang.String
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Mostra se questa proprietà non appartiene all'elenco delle proprietà predefinite nella specifica: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Restituisce:**
boolean