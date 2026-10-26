---
title: IMasterTheme
second_title: Aspose.Slides dla Androida poprzez odwołanie do Java API
description: Reprezentuje motyw nadrzędny.
type: docs
url: /pl/com.aspose.slides/imastertheme/
---
**All Implemented Interfaces:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Reprezentuje motyw nadrzędny.
## Metody

| Metoda | Opis |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Zwraca kolekcję dodatkowych schematów kolorów. |
| [getName()](#getName--) | Zwraca nazwę motywu. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca nazwę motywu. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

Zwraca kolekcję dodatkowych schematów kolorów. Schematy te nie wpływają na wygląd prezentacji, mogą być wybrane jako główny schemat kolorów dla slajdu. Tylko do odczytu [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Zwraca:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

Zwraca nazwę motywu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Zwraca nazwę motywu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |