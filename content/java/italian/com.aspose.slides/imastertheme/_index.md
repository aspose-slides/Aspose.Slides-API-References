---
title: IMasterTheme
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un tema master.
type: docs
url: /it/com.aspose.slides/imastertheme/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Rappresenta un tema master.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Returns the collection of additional color schemes. |
| [getName()](#getName--) | Returns the name of a theme. |
| [setName(String value)](#setName-java.lang.String-) | Returns the name of a theme. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

Restituisce la collezione di schemi di colore aggiuntivi. Questi schemi non influenzano l'aspetto della presentazione, possono essere selezionati come schema di colore principale per una diapositiva. Solo lettura [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Restituisce:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

Restituisce il nome di un tema. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Restituisce il nome di un tema. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |