---
title: IOverrideThemeManager
second_title: Riferimento API di Aspose.Slides per Java
description: Fornisce l'accesso a diversi tipi di temi sovrascritti.
type: docs
url: /it/com.aspose.slides/ioverridethememanager/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Fornisce l'accesso a diversi tipi di temi sovrascritti.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determina se OverrideTheme sovrascrive il tema efficace ereditato o meno. |
| [getOverrideTheme()](#getOverrideTheme--) | Restituisce l'oggetto del tema OverrideTheme. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Restituisce l'oggetto del tema OverrideTheme. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


Determina se OverrideTheme sovrascrive il tema efficace ereditato o non. Per abilitare OverrideTheme per la sovrascrittura usare i metodi OverrideTheme.Init\*(). Per disabilitare OverrideTheme dalla sovrascrittura usare il metodo OverrideTheme.Clear(). Booleano di sola lettura.

**Restituisce:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


Restituisce l'oggetto del tema OverrideTheme. Lettura/scrittura [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Restituisce:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


Restituisce l'oggetto del tema OverrideTheme. Lettura/scrittura [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |