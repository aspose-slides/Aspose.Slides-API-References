---
title: Metered
second_title: Aspose.Slides для Android через Java API Reference
description: Предоставляет методы для установки метерированного ключа.
type: docs
url: /ru/com.aspose.slides/metered/
---
**Наследование:**
java.lang.Object
```
public class Metered
```

Предоставляет методы для установки метерированного ключа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Metered()](#Metered--) | Инициализирует новый экземпляр этого класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Устанавливает публичный и приватный метерированный ключ. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Получает размер файла потребления |
| [getConsumptionCredit()](#getConsumptionCredit--) | Получает кредит потребления |
| [isMeteredLicensed()](#isMeteredLicensed--) | Проверяет, лицензирован ли метеринг |
### Metered() {#Metered--}
```
public Metered()
```


Инициализирует новый экземпляр этого класса.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Устанавливает публичный и приватный метерированный ключ. Если вы приобретаете метерированную лицензию, при запуске приложения этот API должен быть вызван, обычно этого достаточно. Однако если постоянно не удаётся загрузить данные о потреблении и проходит более 24 часов, лицензия будет переключена в статус оценки; чтобы избежать такой ситуации, следует регулярно проверять статус лицензии, и если он находится в статусе оценки, вызвать этот API снова.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| publicKey | java.lang.String | публичный ключ |
| privateKey | java.lang.String | приватный ключ |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Получает размер файла потребления

**Возвращаемое значение:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Получает кредит потребления

**Возвращаемое значение:**
double - количество потребления
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Проверяет, лицензирован ли метеринг

**Возвращаемое значение:**
boolean - Истина или ложь