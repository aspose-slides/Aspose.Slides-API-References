---
title: Cell
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Zelle einer Tabelle dar.
type: docs
weight: 300
url: /de/aspose.slides/cell/
---
## Cell Klasse

Stellt eine Zelle einer Tabelle dar.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Bestimmt, ob ein Textfeld innerhalb einer Zelle zentriert ist oder nicht. Lese **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Gibt das [CellFormat](../cellformat/)-Objekt zurück, das die Formatierungseigenschaften für diese Zelle enthält. Nur-Lesen [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Gibt die Anzahl der Rasterspalten im Tabellengitter der übergeordneten Tabelle zurück, die von der aktuellen Zelle überlappt werden sollen. Diese Eigenschaft ermöglicht das Aussehen zusammengeführter Zellen, da sie vertikale Grenzen anderer Zellen in der Tabelle überragen. Nur-Lesen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Ermittelt die erste Spalte der Zelle. Nur-Lesen [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Gibt den Index der ersten von der Zelle bedeckten Spalte zurück. Nur-Lesen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Ermittelt die erste Zeile der Zelle. Nur-Lesen [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Gibt den Index der ersten von der Zelle bedeckten Zeile zurück. Nur-Lesen **int32_t**. |
| **double** [get_Height](./get_height/)() override | Gibt die Höhe der Zelle zurück. Nur-Lesen **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Gibt true zurück, wenn die Zelle mit einer angepassten Zelle zusammengeführt ist, andernfalls false. Nur-Lesen **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Gibt den unteren Rand in einem [TextFrame](../textframe/) zurück. Lese **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Gibt den linken Rand in einem [TextFrame](../textframe/) zurück. Lese **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Gibt den rechten Rand in einem [TextFrame](../textframe/) zurück. Lese **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Gibt den oberen Rand in einem [TextFrame](../textframe/) zurück. Lese **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Gibt die minimale Höhe einer Zelle zurück. Dies ist die Summe der minimalen Höhen aller von der Zelle bedeckten Zeilen. Nur-Lesen **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Gibt den Abstand von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. Nur-Lesen **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Gibt den Abstand von der oberen Seite einer Tabelle zur oberen Seite einer Zelle zurück. Nur-Lesen **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Gibt die übergeordnete Präsentation einer Zelle zurück. Nur-Lesen [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Gibt die Anzahl der Zeilen zurück, die eine zusammengeführte Zelle überlappt. Dies wird zusammen mit dem vMerge-Attribut anderer Zellen verwendet, um die Anfangszelle einer horizontalen Zusammenführung zu spezifizieren. Nur-Lesen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Gibt die übergeordnete Folie einer Zelle zurück. Nur-Lesen [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Gibt das übergeordnete [Table](../table/)-Objekt für eine Zelle zurück. Nur-Lesen [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Gibt den Textanker-Typ zurück. Lese [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Gibt den Textrahmen einer Zelle zurück. Nur-Lesen [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Gibt den Typ des vertikalen Textes zurück. Lese [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Gibt die Breite der Zelle zurück. Nur-Lesen **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs ist. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruktieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruktieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Bestimmt, ob ein Textfeld innerhalb einer Zelle zentriert ist oder nicht. Schreibe **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Setzt den unteren Rand in einem [TextFrame](../textframe/). Schreibe **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Setzt den linken Rand in einem [TextFrame](../textframe/). Schreibe **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Setzt den rechten Rand in einem [TextFrame](../textframe/). Schreibe **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Setzt den oberen Rand in einem [TextFrame](../textframe/). Schreibe **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Setzt den Textanker-Typ. Schreibe [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Setzt den Typ des vertikalen Textes. Schreibe [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument als Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern auf Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Teilt die Zelle anhand des Spaltenindex in zwei Zellen. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Teilt die Zelle nach Höhe. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Teilt die Zelle anhand des Zeilenindex in zwei Zellen. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Teilt die Zelle nach Breite. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe Auch

* Klasse [IDOMObject](../idomobject/)
* Klasse [ICell](../icell/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)