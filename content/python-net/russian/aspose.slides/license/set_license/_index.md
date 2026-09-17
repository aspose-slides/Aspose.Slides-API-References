---
title: set_license method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Лицензирует компонент.

```python
def set_license(self, license_name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| license_name | **str** | Может быть полным или коротким именем файла или именем встраиваемого ресурса.<br/><br/>            Используйте пустую строку, чтобы перейти в режим оценки. |

### Примечания

Пытается найти лицензию в следующих местах:

1. Явный путь.
2. Папка сборки компонента.
3. Папка вызывающей сборки клиента.
4. Папка основной сборки.
5. Встраиваемый ресурс в вызывающей сборке клиента.

**Примечание:** В .NET Compact Framework поиск лицензии ограничивается следующими местами:

1. Явный путь.
2. Встраиваемый ресурс в вызывающей сборке клиента.

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
* класс [`License`](/slides/python-net/ru/aspose.slides/license)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)