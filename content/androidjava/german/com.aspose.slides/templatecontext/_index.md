---
title: TemplateContext
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt eine Modellobjekt-Schnittstelle für eine Template-Engine dar.
type: docs
url: /de/com.aspose.slides/templatecontext/
---
**Vererbung:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Stellt eine Modellobjekt-Schnittstelle für eine Template-Engine dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Erstellt einen Kind-Template-Kontext. |
| [getObject()](#getObject--) | Gibt das Modellobjekt zurück. |
| [getOutput()](#getOutput--) | Gibt die Sammlung von Ausgabeelementen des Host-Dokuments zurück. |
| [getLocal()](#getLocal--) | Gibt den lokalen Speicher des aktuellen Template-Kontexts zurück. |
| [getGlobal()](#getGlobal--) | Gibt den globalen Speicher des Host-Dokuments zurück. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

Erstellt einen Kind-Template-Kontext.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subModel | TSubModel | Kindmodellobjekt. |

**Rückgabewert:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Neuer Template-Kontext mit dem angegebenen Modell und der Ausgabesammlung des Elternteils sowie dem globalen Speicher.
### getObject() {#getObject--}
```
public final TObject getObject()
```

Gibt das Modellobjekt zurück. Nur-lesbares Object.

**Rückgabewert:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Gibt die Sammlung von Ausgabeelementen des Host-Dokuments zurück. Nur-lesbar [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Rückgabewert:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

Gibt den lokalen Speicher des aktuellen Template-Kontexts zurück. Nur-lesbar [Storage](../../com.aspose.slides/storage).

**Rückgabewert:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Gibt den globalen Speicher des Host-Dokuments zurück. Nur-lesbar [Storage](../../com.aspose.slides/storage).

**Rückgabewert:**
[Storage](../../com.aspose.slides/storage)