---
title: License
second_title: Aspose.Slides для Android через Java – справочник API
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

| Constructor | Описание |
| --- | --- |
| [License()](#License--) | Создаёт новый экземпляр этого класса. |
## Методы

| Method | Описание |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Лицензирует компонент. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Лицензирует компонент. |
| [getVersion()](#getVersion--) | Возвращает версию Aspose.Slides для Android через Java. |
| [resetLicense()](#resetLicense--) | Сбрасывает лицензию. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Создаёт новый экземпляр этого класса.

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
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий лицензию. Используйте null, чтобы переключиться в режим оценки. |

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
| Parameter | Type | Описание |
| --- | --- | --- |
| namePath | java.lang.String | Может быть полным или коротким именем файла или именем встроенного ресурса. Используйте пустую строку, чтобы переключиться в режим оценки. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Возвращает версию Aspose.Slides для Android через Java.

**Возвращает:**
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

**Возвращает:**
boolean