---
title: get_PortionFormat()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy formázási objektumot, amely tartalmazza a szövegrész explicit módon beállított formázási tulajdonságait, öröklődés nélkül. Csak olvasható IPortionFormat.
type: docs
weight: 1
url: /hu/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() metódus

Visszaad egy formázási objektumot, amely tartalmazza a szövegrész explicit módon beállított formázási tulajdonságait, öröklődés nélkül. Csak olvasható [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Megjegyzések

A formázási objektum csak az aktuális részlethez definiált formázási paramétereket tartalmazza, az örökölt adat nem kerül alkalmazásra.

Az örökölt értékekkel együtt a tényleges értékek lekéréséhez használja a [PortionFormat::GetEffective](../../portionformat/geteffective/) metódust.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPortionFormat](../../iportionformat/)
* Osztály [Portion](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)