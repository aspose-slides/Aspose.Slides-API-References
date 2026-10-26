---
title: ICell
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Zelle in einer Tabelle dar.
type: docs
weight: 1639
url: /de/aspose.slides/icell/
---
## ICell Klasse

Stellt eine Zelle in einer Tabelle dar.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Bestimmt, ob eine Textbox innerhalb einer Zelle zentriert ist. Lese **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Gibt das [CellFormat](../cellformat/)-Objekt zurück, das Formatierungseigenschaften für diese Zelle enthält. Nur-Lesen [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Gibt die Anzahl der Gitterspalten im Tabellenraster der übergeordneten Tabelle zurück, die von der aktuellen Zelle übergreifend sein sollen. Diese Eigenschaft ermöglicht es Zellen, das Aussehen von zusammengeführten Zellen zu haben, da sie vertikale Grenzen anderer Zellen in der Tabelle überdecken. Nur-Lesen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Ermittelt die erste Spalte der Zelle. Nur-Lesen [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Gibt den Index der ersten von der Zelle gedeckten Spalte zurück. Nur-Lesen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Ermittelt die erste Zeile der Zelle. Nur-Lesen [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Gibt den Index der ersten von der Zelle gedeckten Zeile zurück. Nur-Lesen **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Gibt die Höhe der Zelle zurück. Nur-Lesen **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Gibt true zurück, wenn die Zelle mit einer angepassten Zelle zusammengeführt ist, sonst false. Nur-Lesen **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Gibt den unteren Rand in einem [TextFrame](../textframe/) zurück. Lese **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Gibt den linken Rand in einem [TextFrame](../textframe/) zurück. Lese **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Gibt den rechten Rand in einem [TextFrame](../textframe/) zurück. Lese **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Gibt den oberen Rand in einem [TextFrame](../textframe/) zurück. Lese **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Gibt die minimale Höhe einer Zelle zurück. Dies ist die Summe der minimalen Höhen aller von der Zelle bedeckten Zeilen. Nur-Lesen **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Gibt den Abstand von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. Nur-Lesen **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Gibt den Abstand von der oberen Seite einer Tabelle zur oberen Seite einer Zelle zurück. Nur-Lesen **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Gibt die Präsentation zurück. Nur-Lesen [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Gibt die Anzahl der Zeilen zurück, die eine zusammengeführte Zelle überspannt. Dies wird in Kombination mit dem vMerge-Attribut anderer Zellen verwendet, um die Anfangszelle einer horizontalen Zusammenführung zu bestimmen. Nur-Lesen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Gibt die Basisfolie zurück. Nur-Lesen [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Gibt das übergeordnete [Table](../table/)-Objekt für eine Zelle zurück. Nur-Lesen [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Gibt den Textanker-Typ zurück. Lese [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Gibt den Textrahmen einer Zelle zurück. Nur-Lesen [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Gibt den Typ des vertikalen Textes zurück. Lese [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Gibt die Breite der Zelle zurück. Nur-Lesen **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefrierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzweise ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den Shared-Referenzzähler um den angegebenen Wert. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Bestimmt, ob eine Textbox innerhalb einer Zelle zentriert ist. Schreibe **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Setzt den unteren Rand in einem [TextFrame](../textframe/). Schreibe **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Setzt den linken Rand in einem [TextFrame](../textframe/). Schreibe **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Setzt den rechten Rand in einem [TextFrame](../textframe/). Schreibe **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Setzt den oberen Rand in einem [TextFrame](../textframe/). Schreibe **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Setzt den Textanker-Typ. Schreibe [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Setzt den Typ des vertikalen Textes. Schreibe [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des Shared-Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den Shared-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den Shared-Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Teilt die Zelle anhand des Spaltenindex in zwei Zellen. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Teilt die Zelle anhand der Höhe. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Teilt die Zelle anhand des Zeilenindex in zwei Zellen. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Teilt die Zelle anhand der Breite. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| virtual [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [ISlideComponent](../islidecomponent/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)