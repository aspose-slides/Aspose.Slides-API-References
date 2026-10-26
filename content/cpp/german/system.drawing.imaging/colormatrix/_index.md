---
title: ColorMatrix
second_title: Aspose.Slides für C++ API-Referenz
description: "Repäsentiert eine 5x5-Matrix, die die Koordinaten des RGBAW-Farbraums enthält. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 27
url: /de/system.drawing.imaging/colormatrix/
---
## ColorMatrix Klasse


Repäsentiert eine 5×5-Matrix, die die Koordinaten für den RGBAW-Farbraum enthält. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/) Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ColorMatrix : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Konstruiert eine neue Instanz der [ColorMatrix](./) Klasse und initialisiert sie mit den Werten der Einheitsmatrix. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Konstruiert eine neue Instanz der [ColorMatrix](./) Klasse und initialisiert sie mit den angegebenen Werten. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen (double), bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **float** [get_Matrix00](./get_matrix00/)() const | Gibt einen Wert in Zeile 0 und Spalte 0 zurück. |
| **float** [get_Matrix01](./get_matrix01/)() const | Gibt einen Wert in Zeile 0 und Spalte 1 zurück. |
| **float** [get_Matrix02](./get_matrix02/)() const | Gibt einen Wert in Zeile 0 und Spalte 2 zurück. |
| **float** [get_Matrix03](./get_matrix03/)() const | Gibt einen Wert in Zeile 0 und Spalte 3 zurück. |
| **float** [get_Matrix04](./get_matrix04/)() const | Gibt einen Wert in Zeile 0 und Spalte 4 zurück. |
| **float** [get_Matrix10](./get_matrix10/)() const | Gibt einen Wert in Zeile 1 und Spalte 0 zurück. |
| **float** [get_Matrix11](./get_matrix11/)() const | Gibt einen Wert in Zeile 1 und Spalte 1 zurück. |
| **float** [get_Matrix12](./get_matrix12/)() const | Gibt einen Wert in Zeile 1 und Spalte 2 zurück. |
| **float** [get_Matrix13](./get_matrix13/)() const | Gibt einen Wert in Zeile 1 und Spalte 3 zurück. |
| **float** [get_Matrix14](./get_matrix14/)() const | Gibt einen Wert in Zeile 1 und Spalte 4 zurück. |
| **float** [get_Matrix20](./get_matrix20/)() const | Gibt einen Wert in Zeile 2 und Spalte 0 zurück. |
| **float** [get_Matrix21](./get_matrix21/)() const | Gibt einen Wert in Zeile 2 und Spalte 1 zurück. |
| **float** [get_Matrix22](./get_matrix22/)() const | Gibt einen Wert in Zeile 2 und Spalte 2 zurück. |
| **float** [get_Matrix23](./get_matrix23/)() const | Gibt einen Wert in Zeile 2 und Spalte 3 zurück. |
| **float** [get_Matrix24](./get_matrix24/)() const | Gibt einen Wert in Zeile 2 und Spalte 4 zurück. |
| **float** [get_Matrix30](./get_matrix30/)() const | Gibt einen Wert in Zeile 3 und Spalte 0 zurück. |
| **float** [get_Matrix31](./get_matrix31/)() const | Gibt einen Wert in Zeile 3 und Spalte 1 zurück. |
| **float** [get_Matrix32](./get_matrix32/)() const | Gibt einen Wert in Zeile 3 und Spalte 2 zurück. |
| **float** [get_Matrix33](./get_matrix33/)() const | Gibt einen Wert in Zeile 3 und Spalte 3 zurück. |
| **float** [get_Matrix34](./get_matrix34/)() const | Gibt einen Wert in Zeile 3 und Spalte 4 zurück. |
| **float** [get_Matrix40](./get_matrix40/)() const | Gibt einen Wert in Zeile 4 und Spalte 0 zurück. |
| **float** [get_Matrix41](./get_matrix41/)() const | Gibt einen Wert in Zeile 4 und Spalte 1 zurück. |
| **float** [get_Matrix42](./get_matrix42/)() const | Gibt einen Wert in Zeile 4 und Spalte 2 zurück. |
| **float** [get_Matrix43](./get_matrix43/)() const | Gibt einen Wert in Zeile 4 und Spalte 3 zurück. |
| **float** [get_Matrix44](./get_matrix44/)() const | Gibt einen Wert in Zeile 4 und Spalte 4 zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| **float** [idx_get](./idx_get/)(int, int) | Gibt den Wert in der angegebenen Zeile und Spalte zurück. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Setzt den angegebenen Wert an der angegebenen Position in der Matrix. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächter-Objekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Setzt einen Wert in Zeile 0, Spalte 0. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Setzt einen Wert in Zeile 0, Spalte 1. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Setzt einen Wert in Zeile 0, Spalte 2. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Setzt einen Wert in Zeile 0, Spalte 3. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Setzt einen Wert in Zeile 0, Spalte 4. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Setzt einen Wert in Zeile 1, Spalte 0. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Setzt einen Wert in Zeile 1, Spalte 1. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Setzt einen Wert in Zeile 1, Spalte 2. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Setzt einen Wert in Zeile 1, Spalte 3. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Setzt einen Wert in Zeile 1, Spalte 4. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Setzt einen Wert in Zeile 2, Spalte 0. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Setzt einen Wert in Zeile 2, Spalte 1. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Setzt einen Wert in Zeile 2, Spalte 2. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Setzt einen Wert in Zeile 2, Spalte 3. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Setzt einen Wert in Zeile 2, Spalte 4. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Setzt einen Wert in Zeile 3, Spalte 0. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Setzt einen Wert in Zeile 3, Spalte 1. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Setzt einen Wert in Zeile 3, Spalte 2. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Setzt einen Wert in Zeile 3, Spalte 3. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Setzt einen Wert in Zeile 3, Spalte 4. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Setzt einen Wert in Zeile 4, Spalte 0. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Setzt einen Wert in Zeile 4, Spalte 1. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Setzt einen Wert in Zeile 4, Spalte 2. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Setzt einen Wert in Zeile 4, Spalte 3. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Setzt einen Wert in Zeile 4, Spalte 4. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt shared). Ermöglicht das Wechseln von Zeigern in Containern zum schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächter-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Drawing::Imaging](../)
* Bibliothek [Aspose.Slides](../../)