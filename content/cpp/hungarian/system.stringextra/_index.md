---
title: "System::StringExtra"
second_title: Aspose.Slides a C++ API hivatkozás
description: 
type: docs
weight: 911
url: /hu/system.stringextra/
---
## Funkciók

| Függvény | Leírás |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Összefűzi a karakterlánc-tömböt. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Összefűzi a karakterláncokat. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Összefűzi a karakterláncokat. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Összefűzi a karakterláncokat. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Több objektumot alakít át karakterlánccá és fűzi össze az eredményül kapott karakterláncokat. Specializáció a [SmartPtr](../system/smartptr/) típusokhoz. |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Több objektumot alakít át karakterlánccá és fűzi össze az eredményül kapott karakterláncokat. Specializáció numerikus típusokhoz. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Több objektumot alakít át karakterlánccá és fűzi össze az eredményül kapott karakterláncokat. Specializáció struktúrák és egyéb érték típusokhoz. |