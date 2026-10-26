---
title: set_metered_key method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
Устанавливает измеряемый публичный и приватный ключ.
            Если вы приобретаете измеряемую лицензию, при запуске приложения этот API должен быть вызван, обычно этого бывает достаточно. 
            Однако, если постоянно не удаётся загрузить данные о потреблении и прошло более 24 часов, лицензия будет переведена в статус оценки, 
            чтобы избежать такого случая, следует регулярно проверять статус лицензии; если он находится в статусе оценки, вызовите этот API снова.


```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| public_key | **str** | public key |
| private_key | **str** | private key |



### Смотрите также
* класс [`Metered`](/slides/python-net/ru/aspose.slides/metered)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)