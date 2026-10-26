---
title: HolderInitializer
second_title: Aspose.Slides für C++ API Referenz
description: Diese Klasse wird verwendet, um eine dauerhafte Referenz auf die Objektinstanz zu erhalten, egal ob es sich um ein lvalue oder rvalue handelt. Um eine solche Referenz zu erhalten, verwenden Sie die Methode 'HoldIfTemporary', die dort drei Überladungen hat. Zwei davon nehmen ein rvalue als Parameter und geben einfach die Referenz darauf zurück. Die dritte nimmt im Gegensatz ein lvalue als Parameter, erstellt eine Kopie des Zeigers und gibt dann die Referenz auf diese Kopie zurück. Außerdem besitzt die Klasse die Methode 'Hold', um den übergebenen Wert bedingungslos zu halten (verwendet, um Werte lokaler Variablen auf dem Stack oder deren Kindreferenzen zu kopieren).
type: docs
weight: 1639
url: /de/system/holderinitializer/
---
## HolderInitializer Struktur

Diese Klasse wird verwendet, um eine dauerhafte Referenz auf die Objektinstanz zu erhalten, egal ob es sich um ein lvalue oder rvalue handelt. Um eine solche Referenz zu erhalten, benutzen Sie die Methode `HoldIfTemporary`, die dort drei Überladungen hat. Zwei davon nehmen ein rvalue als Parameter und geben einfach die Referenz darauf zurück. Die dritte nimmt im Gegensatz ein lvalue als Parameter, erstellt eine Kopie des Zeigers und gibt dann die Referenz auf diese Kopie zurück. Außerdem besitzt die Klasse die Methode `Hold`, um den übergebenen Wert bedingungslos zu halten (verwendet, um Werte lokaler Variablen auf dem Stack oder deren Kindreferenzen zu kopieren).

```cpp
template<typename T,bool>class HolderInitializer
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Objekts, das gehalten werden soll. |
| R | Wahr, wenn T ein Referenztyp ist ([SmartPtr](../smartptr/)-Spezialisierung oder [System::String](../string/)-Typ) und das Halten temporärer Referenzen tatsächlich erforderlich ist, sonst falsch. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Kopiert das übergebene lvalue in den Halter und gibt dann die Halter-Referenz zurück. Der Aufrufer sollte diese Methode verwenden, um den übergebenen Wert bedingungslos zu halten. |
|  [HolderInitializer](./holderinitializer/)(T\&) | Initialisiert die Halter-Referenz mit der übergebenen. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Gibt eine Referenz auf das rvalue (const) zurück. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Gibt eine Referenz auf das rvalue (nicht const) zurück. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Kopiert das übergebene lvalue in den Halter und gibt dann die Halter-Referenz zurück. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)