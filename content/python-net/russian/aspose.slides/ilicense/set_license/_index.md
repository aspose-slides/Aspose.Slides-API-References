---
title: set_license method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Лицензирует компонент.


```python
def set_license(self, license_name):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| license_name | **str** | Может быть полным или сокращённым именем файла или именем встроенного ресурса.<br/><br/>Используйте пустую строку, чтобы переключиться в режим оценки. |

### Примечания

Пытается найти лицензию в следующих местах:


1. Явный путь.


2. Папка сборки компонента.


3. Папка вызывающей сборки клиента.


4. Папка основной сборки.


5. Встроенный ресурс в вызывающей сборке клиента.


**Примечание:** В .NET Compact Framework попытка найти лицензию осуществляется только в этих местах:


1. Явный путь.


2. Встроенный ресурс в вызывающей сборке клиента.


## set_license(self, stream) {#iorawiobase}
Лицензирует компонент.


```python
def set_license(self, stream):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Поток, содержащий лицензию. |

### Примечания

Используйте этот метод для загрузки лицензии из потока.



### См. также
* класс [`ILicense`](/slides/python-net/ru/aspose.slides/ilicense)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)