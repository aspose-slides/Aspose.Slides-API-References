---
title: ImageAttributes
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt Informationen darüber bereit, wie Bildfarben während der Darstellung manipuliert werden. Objekte dieser Klasse sollten nur mit der System::MakeObject()-Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies Laufzeitfehler und/oder Assertion-Fehler zur Folge hat. Verpacken Sie diese Klasse immer in einen System::SmartPtr-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 105
url: /de/system.drawing.imaging/imageattributes/
---
## ImageAttributes Klasse


Stellt Informationen darüber bereit, wie Bildfarben während der Darstellung manipuliert werden. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../../system/makeobject/)-Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies Laufzeitfehler und/oder Assertion-Fehler zur Folge hat. Verpacken Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ImageAttributes : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [ClearBrushRemapTable](./clearbrushremaptable/)() | NICHT IMPLEMENTIERT. |
| void [ClearColorKey](./clearcolorkey/)([ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [ClearColorMatrix](./clearcolormatrix/)([ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [ClearGamma](./cleargamma/)([ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [ClearNoOp](./clearnoop/)([ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [ClearOutputChannel](./clearoutputchannel/)([ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [ClearOutputChannelColorProfile](./clearoutputchannelcolorprofile/)([ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [ClearRemapTable](./clearremaptable/)([ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [ClearThreshold](./clearthreshold/)([ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| [SharedPtr](../../system/sharedptr/)\<[ImageAttributes](./)\> [Clone](./clone/)() | Erstellt eine Kopie des aktuellen Objekts. |
| void [Dispose](./dispose/)() | Gibt alle vom aktuellen Objekt erworbenen Betriebssystem-Ressourcen frei. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mittels C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenz-Typ-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Wert-Typ-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, wobei zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, wobei zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| void [GetAdjustedPalette](./getadjustedpalette/)(const [SharedPtr](../../system/sharedptr/)\<[ColorPalette](../colorpalette/)\>\&, [ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Datenstruktur des Referenzzählers, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
|  [ImageAttributes](./imageattributes/)() | Standard-Konstruktor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs ist. Analog zum C#-`is`-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperr-Anweisung `lock()` von C#. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Subklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Subklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht einen Wert-Typ-Objekt per Referenz mit `nullptr`. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und `nullptr`. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| void [SetBrushRemapTable](./setbrushremaptable/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[ColorMap](../colormap/)\>\>\&) | NICHT IMPLEMENTIERT. |
| void [SetColorKey](./setcolorkey/)([Color](../../system.drawing/color/), [Color](../../system.drawing/color/), [ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [SetColorMatrices](./setcolormatrices/)(const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, [ColorMatrixFlag](../colormatrixflag/), [ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [SetColorMatrix](./setcolormatrix/)(const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, [ColorMatrixFlag](../colormatrixflag/), [ColorAdjustType](../coloradjusttype/)) | Setzt die Farb-Anpassungs-Matrix. |
| void [SetGamma](./setgamma/)(**float**, [ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [SetNoOp](./setnoop/)([ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [SetOutputChannel](./setoutputchannel/)([ColorChannelFlag](../colorchannelflag/), [ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [SetOutputChannelColorProfile](./setoutputchannelcolorprofile/)(const [String](../../system/string/)\&, [ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [SetRemapTable](./setremaptable/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[ColorMap](../colormap/)\>\>\&, [ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| void [SetThreshold](./setthreshold/)(**float**, [ColorAdjustType](../coloradjusttype/)) | NICHT IMPLEMENTIERT. |
| void [SetWrapMode](./setwrapmode/)([Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/), [Color](../../system.drawing/color/), **bool**) | Legt den Umbruch-Modus und die Farbe fest, die bestimmen, wie eine Textur über einer Form oder an Formgrenzen gekachelt wird. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den geteilten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-`lock()`-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Drawing::Imaging](../)
* Bibliothek [Aspose.Slides](../../)