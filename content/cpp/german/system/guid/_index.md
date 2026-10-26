---
title: Guid
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen global eindeutigen Bezeichner dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 885
url: /de/system/guid/
---
## Guid Klasse

Stellt einen Globally Unique Identifier dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class Guid
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Führt einen arithmetischen Vergleich der von dem aktuellen und dem angegebenen Objekt dargestellten GUIDs durch. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Bestimmt, ob die von dem aktuellen und dem angegebenen Objekt dargestellten GUIDs gleich sind. |
| int [GetHashCode](./gethashcode/)() const | Gibt einen Hashcode für das aktuelle Objekt zurück. |
|  [Guid](./guid/)() | Konstruiert ein Objekt, das eine GUID darstellt, die ausschließlich aus Nullen besteht. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Konstruiert ein Objekt, das eine GUID darstellt, die als Array von vorzeichenlosen 8-Bit-Ganzzahlen angegeben ist. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Konstruiert ein Objekt, das eine GUID darstellt, die als Array-Ansicht von vorzeichenlosen 8-Bit-Ganzzahlen angegeben ist. |
|  [Guid](./guid/)(const [String](../string/)\&) | Konstruiert ein Objekt, das eine GUID darstellt, die als Zeichenkette angegeben ist. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Konstruiert eine Instanz der [Guid](./) Klasse aus den angegebenen GUID-Komponenten. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Konstruiert eine Instanz der [Guid](./) Klasse aus den angegebenen GUID-Komponenten. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Konstruiert eine Instanz der [Guid](./) Klasse aus den angegebenen vorzeichenlosen Ganzzahlen und Bytes. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Konstruiert eine Instanz der [Guid](./) Klasse aus den angegebenen vorzeichenlosen Ganzzahlen und Bytes. |
|  [Guid](./guid/)(const [Guid](./)\&) | Konstruiert ein Objekt, das dieselbe GUID wie das angegebene Objekt darstellt. |
| static [Guid](./) [NewGuid](./newguid/)() | Erzeugt eine neue GUID und gibt ein [Guid](./) Objekt zurück, das sie darstellt. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Bestimmt, ob die von dem aktuellen und dem angegebenen Objekt dargestellten GUIDs nicht gleich sind. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Weist dem aktuellen Objekt den GUID-Wert zu, der durch das angegebene [Guid](./) Objekt dargestellt wird. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Bestimmt, ob die von dem aktuellen und dem angegebenen Objekt dargestellten GUIDs gleich sind. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkettenrepräsentation einer GUID in ein äquivalentes [Guid](./) Objekt. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Konvertiert die von dem aktuellen Objekt dargestellte GUID in ein Array von Bytes. |
| [String](../string/) [ToString](./tostring/)() const | Konvertiert die von dem aktuellen Objekt dargestellte GUID in ihre Zeichenkettenrepräsentation. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Konvertiert die von dem aktuellen Objekt dargestellte GUID in ihre Zeichenkettenrepräsentation unter Verwendung des angegebenen Zeichenkettenformats. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Konvertiert die von dem aktuellen Objekt dargestellte GUID in ihre Zeichenkettenrepräsentation unter Verwendung des angegebenen Zeichenkettenformats und der Kultur. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Versucht, die angegebene Zeichenkette in ein [Guid](./) Objekt zu konvertieren. |
|  [~Guid](./~guid/)() | Destruktor. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Empty](./empty/) | Stellt eine GUID dar, die den Wert 0 hat. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)