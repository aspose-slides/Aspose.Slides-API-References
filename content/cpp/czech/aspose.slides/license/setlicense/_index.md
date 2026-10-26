---
title: SetLicense()
second_title: Aspose.Slides pro C++ API Reference
description: Licencuje komponentu.
type: docs
weight: 14
url: /cs/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) metoda

Licencuje komponentu.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Může být úplný nebo zkrácený název souboru nebo název vloženého prostředku. Použijte prázdný řetězec pro přepnutí do evaluačního režimu. |

## Poznámky

Pokouší se najít licenci v následujících umístěních:

1. Explicitní cesta.
2. Složka sestavení komponenty.
3. Složka sestavení volajícího klienta.
4. Složka vstupního sestavení.
5. Vložený prostředek v sestavení volajícího klienta.

**Poznámka:**V .NET Compact Framework se pokouší najít licenci pouze v těchto umístěních:

1. Explicitní cesta.
2. Vložený prostředek v sestavení volajícího klienta.

V tomto příkladu se bude snažit najít licenční soubor pojmenovaný MyLicense.lic ve složce, která obsahuje komponentu, ve složce, která obsahuje volající sestavení, ve složce vstupního sestavení a poté ve vložených prostředcích volajícího sestavení. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) metoda

Licencuje komponentu.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Proud obsahující licenci. |

## Poznámky

Použijte tuto metodu k načtení licence z proudu.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [License](../)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)