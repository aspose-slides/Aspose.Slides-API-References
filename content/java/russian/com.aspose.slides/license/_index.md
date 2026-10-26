---
title: License
second_title: Справочник API Aspose.Slides для Java
description: Предоставляет методы для лицензирования компонента.
type: docs
url: /ru/com.aspose.slides/license/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Предоставляет методы для лицензирования компонента.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [License()](#License--) | Инициализирует новый экземпляр этого класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Лицензирует компонент. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Лицензирует компонент. |
| [getVersion()](#getVersion--) | Возвращает версию Aspose.Slides для Java. |
| [resetLicense()](#resetLicense--) | Сбрасывает лицензию. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

Инициализирует новый экземпляр этого класса.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```

Лицензирует компонент.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий лицензию. Используйте null для переключения в режим оценки. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

Лицензирует компонент.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| namePath | java.lang.String | Может быть полным или коротким именем файла или именем внедренного ресурса. Используйте пустую строку для переключения в режим оценки. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

Возвращает версию Aspose.Slides для Java.

**Возвращаемое значение:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

Сбрасывает лицензию. Используйте этот метод для сброса лицензии в компоненте.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

Проверяет, применена ли лицензия к компоненту

**Возвращаемое значение:**
boolean