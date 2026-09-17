---
title: Metered class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/metered/
---
## Metered Klasse

Stellt Methoden zum Festlegen des gemessenen Schlüssels bereit.

Der Typ Metered stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides/metered/__init__/#) | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/slides/python-net/de/aspose.slides/metered/set_metered_key/#str-str) | Setzt den öffentlichen und privaten metered-Schlüssel.<br/>            Wenn Sie eine metered-Lizenz kaufen, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise ist das ausreichend.<br/>            Wenn jedoch das Hochladen von Verbrauchsdaten immer fehlschlägt und die 24-Stunden-Grenze überschritten wird, wird die Lizenz auf den Evaluierungsstatus gesetzt.<br/>            Um diesen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf. |
| [`get_consumption_quantity()`](/slides/python-net/de/aspose.slides/metered/get_consumption_quantity/#) | Ermittelt die Größe der Verbrauchsdatei |
| [`get_consumption_credit()`](/slides/python-net/de/aspose.slides/metered/get_consumption_credit/#) | Ermittelt das Verbrauchsguthaben |
| [`get_product_name(self)`](/slides/python-net/de/aspose.slides/metered/get_product_name/#) |  |
| [`is_metered_licensed()`](/slides/python-net/de/aspose.slides/metered/is_metered_licensed/#) | Überprüft, ob metered lizenziert ist |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)