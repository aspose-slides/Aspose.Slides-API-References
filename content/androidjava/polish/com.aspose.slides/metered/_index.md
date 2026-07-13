---
title: Metered
second_title: Aspose.Slides dla Androida – odniesienie do Java API
description: Udostępnia metody do ustawiania klucza pomiarowego.
type: docs
url: /pl/com.aspose.slides/metered/
---
**Dziedziczenie:**
java.lang.Object
```
public class Metered
```

Udostępnia metody do ustawiania klucza pomiarowego.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [Metered()](#Metered--) | Inicjalizuje nową instancję tej klasy. |
## Metody

| Metoda | Opis |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ustawia publiczny i prywatny klucz pomiarowy. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Pobiera rozmiar pliku zużycia |
| [getConsumptionCredit()](#getConsumptionCredit--) | Pobiera kredyt zużycia |
| [isMeteredLicensed()](#isMeteredLicensed--) | Sprawdza, czy metered jest licencjonowany |
### Metered() {#Metered--}
```
public Metered()
```

Inicjalizuje nową instancję tej klasy.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Ustawia publiczny i prywatny klucz pomiarowy. Jeśli zakupisz licencję pomiarową, przy uruchamianiu aplikacji należy wywołać to API; zazwyczaj to wystarczy. Jednakże, jeśli ciągle nie udaje się wysłać danych zużycia i przekroczą 24 godziny, licencja zostanie ustawiona w tryb ewaluacji; aby uniknąć takiej sytuacji, należy regularnie sprawdzać status licencji, a jeśli jest w trybie ewaluacji, ponownie wywołać to API.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| publicKey | java.lang.String | klucz publiczny |
| privateKey | java.lang.String | klucz prywatny |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

Pobiera rozmiar pliku zużycia

**Zwraca:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

Pobiera kredyt zużycia

**Zwraca:**
double - ilość zużycia
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

Sprawdza, czy metered jest licencjonowany

**Zwraca:**
boolean - Prawda lub fałsz