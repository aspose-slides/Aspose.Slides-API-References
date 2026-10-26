---
title: MakeRelativeUri()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa różnicę pomiędzy identyfikatorami URI reprezentowanymi przez bieżący obiekt oraz określone obiekty Uri.
type: docs
weight: 352
url: /pl/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) metoda


Określa różnicę pomiędzy URI reprezentowanymi przez bieżący i wskazany [Uri](../) obiekt.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Obiekt porównania |

### Wartość zwracana

Jeśli nazwa hosta i schemat URI reprezentowanych przez bieżący obiekt i **toUri** są takie same, metoda zwraca względny [Uri](../), który po dołączeniu do bieżącej instancji URI daje **toUri**. Jeśli nazwa hosta lub schemat jest różny, metoda zwraca obiekt [Uri](../), który reprezentuje parametr **uri**.

## Zobacz także

* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [Uri](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)