---
title: BitConverter
second_title: Référence API Aspose.Slides pour C++
description: Contient des méthodes qui effectuent des conversions d'une séquence d'octets vers un type valeur et vice-versa. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de ce type par quelque moyen que ce soit.
type: docs
weight: 66
url: /fr/system/bitconverter/
---
## BitConverter classe

Contient des methodes qui effectuent des conversions d'une sequence d'octets vers un type valeur et vice-versa. C'est un type statique sans services d'instance. Vous ne devez jamais creer d'instances de ce type par quelque moyen que ce soit.

```cpp
class BitConverter
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Indique le type d'endianite de l'architecture actuelle. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Renvoie une valeur entiere 64 bits dont la representation binaire est egale a la representation binaire de la valeur a virgule flottante double precision specifiee. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Convertit la valeur booleenne specifiee en un tableau d'octets. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Convertit la valeur char_t specifiee en un tableau d'octets. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Convertit la valeur entiere 16 bits specifiee en un tableau d'octets. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Convertit la valeur entiere 32 bits specifiee en un tableau d'octets. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Convertit la valeur entiere 64 bits specifiee en un tableau d'octets. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Convertit la valeur entiere non signee 16 bits specifiee en un tableau d'octets. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Convertit la valeur entiere non signee 32 bits specifiee en un tableau d'octets. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Convertit la valeur entiere non signee 64 bits specifiee en un tableau d'octets. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Convertit la valeur en virgule flottante simple precision specifiee en un tableau d'octets. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Convertit la valeur en virgule flottante double precision specifiee en un tableau d'octets. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Renvoie une valeur a virgule flottante double precision dont la valeur est equivalente a la valeur specifiee. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convertit un octet du tableau specifie a partir de l'index specifie en une valeur booleenne. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convertit un octet du tableau specifie a partir de l'index specifie en une valeur booleenne. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convertit deux octets du tableau specifie a partir de l'index specifie en une valeur char_t. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convertit deux octets du tableau specifie a partir de l'index specifie en une valeur char_t. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convertit huit octets du tableau specifie a partir de l'index specifie en une valeur a virgule flottante double precision. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convertit huit octets du tableau specifie a partir de l'index specifie en une valeur a virgule flottante double precision. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convertit deux octets du tableau specifie a partir de l'index specifie en une valeur entiere 16 bits. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convertit deux octets du tableau specifie a partir de l'index specifie en une valeur entiere 16 bits. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convertit quatre octets du tableau specifie a partir de l'index specifie en une valeur entiere 32 bits. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convertit quatre octets du tableau specifie a partir de l'index specifie en une valeur entiere 32 bits. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convertit huit octets du tableau specifie a partir de l'index specifie en une valeur entiere 64 bits. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convertit huit octets du tableau specifie a partir de l'index specifie en une valeur entiere 64 bits. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convertit quatre octets du tableau specifie a partir de l'index specifie en une valeur a virgule flottante simple precision. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convertit quatre octets du tableau specifie a partir de l'index specifie en une valeur a virgule flottante simple precision. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Convertit toutes les valeurs du tableau d'octets specifie en leur representation sous forme de chaine hexadecimale. La casse des lettres a utiliser dans la notation hexadecimale et le separateur insere entre chaque paire d'octets voisins sont specifies via les arguments correspondants. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convertit les valeurs du tableau d'octets specifie en leur representation sous forme de chaine hexadecimale a partir de l'index specifie. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Convertit une plage de valeurs du tableau d'octets specifie en leur representation sous forme de chaine hexadecimale. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convertit deux octets du tableau specifie a partir de l'index specifie en une valeur entiere non signee 16 bits. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convertit deux octets du tableau specifie a partir de l'index specifie en une valeur entiere non signee 16 bits. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convertit quatre octets du tableau specifie a partir de l'index specifie en une valeur entiere non signee 32 bits. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convertit quatre octets du tableau specifie a partir de l'index specifie en une valeur entiere non signee 32 bits. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convertit huit octets du tableau specifie a partir de l'index specifie en une valeur entiere non signee 64 bits. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convertit huit octets du tableau specifie a partir de l'index specifie en une valeur entiere non signee 64 bits. |

## Champs

| Champ | Description |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Indique le type d'endianite de l'architecture actuelle. true si l'architecture est little endian, false sinon. |

## Remarques



```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // Créer des valeurs à afficher.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Afficher la valeur et ses octets.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliotheque [Aspose.Slides](../../)