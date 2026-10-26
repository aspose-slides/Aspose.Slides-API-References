---
title: SetLicense()
second_title: Aspose.Slides для C++ справочник API
description: Лицензирует компонент.
type: docs
weight: 14
url: /ru/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) метод


Лицензирует компонент.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Может быть полным или коротким именем файла или именем встроенного ресурса. Используйте пустую строку, чтобы переключиться в режим оценки. |
## Примечания



Пытается найти лицензию в следующих местах:

1. Явный путь.

2. Папка сборки компонента.

3. Папка вызывающей сборки клиента.

4. Папка входной сборки.

5. Встроенный ресурс в вызывающей сборке клиента.

**Примечание:**В .NET Compact Framework поиск лицензии выполняется только в следующих местах:

1. Явный путь.

2. Встроенный ресурс в вызывающей сборке клиента.

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) метод


Лицензирует компонент.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, содержащий лицензию. |
## Примечания



Используйте этот метод для загрузки лицензии из потока.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [License](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)