---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: Предоставляет методы для лицензирования компонента.
type: docs
url: /ru/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Предоставляет методы для лицензирования компонента.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Лицензирует компонент. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Лицензирует компонент. |
| [resetLicense()](#resetLicense--) | Сбросить лицензию |
| [isLicensed()](#isLicensed--) | Проверить, применена ли лицензия к компоненту |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Лицензирует компонент.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseName | java.lang.String | Может быть полным или коротким именем файла или именем встроенного ресурса. Используйте пустую строку для перехода в режим оценки.

--------------------

Пытается найти лицензию в следующих местах:

1. Явный путь.

2. Папка сборки компонента.

3. Папка вызывающей сборки клиента.

4. Папка входной сборки.

5. Встроенный ресурс в вызывающей сборке клиента. |
### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Лицензирует компонент.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий лицензию.

--------------------

Используйте этот метод для загрузки лицензии из потока. |
### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Сбросить лицензию

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


--------------------

Используйте этот метод для сброса лицензии в компоненте

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Проверить, применена ли лицензия к компоненту

**Возвращаемое значение:**
boolean — true, если компонент лицензирован, иначе false