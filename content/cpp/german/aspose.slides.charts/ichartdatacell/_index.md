---
title: IChartDataCell
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Zelle für Diagrammdaten dar.
type: docs
weight: 664
url: /de/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell Klasse

Stellt eine Zelle für Diagrammdaten dar.

```cpp
class IChartDataCell : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [Calculate](./calculate/)(**bool**) | Wenn die Zelle eine Formel enthaelt, wird der Wert basierend auf dieser Formel aktualisiert. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemess IEC 60559:1989 NaN zu keinem Wert, einschliesslich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemess IEC 60559:1989 NaN zu keinem Wert, einschliesslich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur fuer interne Zwecke. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorksheet](../ichartdataworksheet/)\> [get_ChartDataWorksheet](./get_chartdataworksheet/)() | Gibt das Arbeitsblatt zurueck. Nur lesbar [IChartDataWorksheet](../ichartdataworksheet/). |
| virtual **int32_t** [get_Column](./get_column/)() | Gibt den Index der Spalte des Arbeitsblatts zurueck, in der sich die Zelle befindet. Nur lesbar **int32_t**. |
| virtual [System::String](../../system/string/) [get_CustomNumberFormat](./get_customnumberformat/)() | Ruft das benutzerdefinierte Anzeigeformat fuer Zahlen und Daten ab. Wenn der Wert leer ist, wird der Wert PresetNumberFormat verwendet. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Formula](./get_formula/)() | Ruft die Formel im A1-Stil ab. |
| virtual **bool** [get_IsHidden](./get_ishidden/)() | Ermittelt, ob die Zelle ausgeblendet ist. Nur lesbar **bool**. |
| virtual **uint8_t** [get_PresetNumberFormat](./get_presetnumberformat/)() | Ruft das integrierte Anzeigeformat fuer Zahlen und Daten ab. Die Vorgabe-Nummer muss in [0..22] oder [37..49] liegen. Lesen **uint8_t**. |
| virtual [System::String](../../system/string/) [get_R1C1Formula](./get_r1c1formula/)() | Ruft die Formel im R1C1-Stil ab. |
| virtual **int32_t** [get_Row](./get_row/)() | Gibt den Index der Zeile des Arbeitsblatts zurueck, in der sich die Zelle befindet. Nur lesbar **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() | Ruft den Wert einer Zelle ab. Lesen [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzaehler-Datenstruktur ab, die mit dem Objekt verknuepft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermoeglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ruft den tatsaechlichen Typ des Objekts ab. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prueft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wachter-Objekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermoeglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermoeglicht das Kopierkonstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermoeglicht das Kopierkonstruktion von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) fuer den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) fuer den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die Shared-Referenzzaehler um den angegebenen Wert. |
| virtual void [set_CustomNumberFormat](./set_customnumberformat/)([System::String](../../system/string/)) | Setzt das benutzerdefinierte Anzeigeformat fuer Zahlen und Daten. Wenn der Wert leer ist, wird der Wert PresetNumberFormat verwendet. Schreiben [System::String](../../system/string/). |
| virtual void [set_Formula](./set_formula/)([System::String](../../system/string/)) | Setzt die Formel im A1-Stil. |
| virtual void [set_PresetNumberFormat](./set_presetnumberformat/)(**uint8_t**) | Setzt das integrierte Anzeigeformat fuer Zahlen und Daten. Die Vorgabe-Nummer muss in [0..22] oder [37..49] liegen. Schreiben **uint8_t**. |
| virtual void [set_R1C1Formula](./set_r1c1formula/)([System::String](../../system/string/)) | Setzt die Formel im R1C1-Stil. |
| virtual void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Setzt den Wert einer Zelle. Schreiben [System::Object](../../system/object/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermoeglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des Shared-Referenzzaehlers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhoeht den Shared-Referenzzaehler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den Shared-Referenzzaehler und gibt ihn zurueck. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermoeglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wachter-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhoeht den Weak-Referenzzaehler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzaehler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)