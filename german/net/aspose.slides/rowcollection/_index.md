---
title: RowCollection
second_title: Aspose.Slides für .NET-API-Referenz
description: Repräsentiert die Sammlung von Tabellenzeilen.
type: docs
weight: 9020
url: /de/net/aspose.slides/rowcollection/
---
## RowCollection class

Repräsentiert die Sammlung von Tabellenzeilen.

```csharp
public sealed class RowCollection : DomObject<Table>, IRowCollection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.slides/rowcollection/count) { get; } | Ruft die Anzahl der Zeilen ab, die tatsächlich in der Sammlung enthalten sind. SchreibgeschütztInt32 . |
| [IsSynchronized](../../aspose.slides/rowcollection/issynchronized) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (threadsicher) ist. SchreibgeschütztBoolean . |
| [Item](../../aspose.slides/rowcollection/item) { get; } | Gibt die Zeile am angegebenen Index zurück. Schreibgeschützt[`Row`](../row) . |
| [SyncRoot](../../aspose.slides/rowcollection/syncroot) { get; } | Gibt einen Synchronisationsstamm zurück. SchreibgeschütztObject . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddClone](../../aspose.slides/rowcollection/addclone)(IRow, bool) | Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am Ende einer Tabelle ein. |
| [CopyTo](../../aspose.slides/rowcollection/copyto)(Array, int) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [GetEnumerator](../../aspose.slides/rowcollection/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [InsertClone](../../aspose.slides/rowcollection/insertclone)(int, IRow, bool) | Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie an der angegebenen Position in eine Tabelle ein. |
| [RemoveAt](../../aspose.slides/rowcollection/removeat)(int, bool) | Entfernt eine Zeile an der angegebenen Position aus einer Tabelle. |

### Siehe auch

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Table](../table)
* interface [IRowCollection](../irowcollection)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->