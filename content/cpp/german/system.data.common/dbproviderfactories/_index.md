---
title: DbProviderFactories
second_title: Aspose.Slides für C++ API-Referenz
description: "API zum Abrufen von DB-Provider-Fabriken. Objekte dieser Klasse sollten nur mit der System::MakeObject()-Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 53
url: /de/system.data.common/dbproviderfactories/
---
## DbProviderFactories Klasse


API zum Abrufen von DB-Provider-Fabriken. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/)-Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Umwickeln Sie immer diese Klasse in einen [System::SmartPtr](../../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class DbProviderFactories
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | Ermittelt die DB-Provider-Fabrik nach Namen. |
## Siehe auch

* Namensraum [System::Data::Common](../)
* Bibliothek [Aspose.Slides](../../)