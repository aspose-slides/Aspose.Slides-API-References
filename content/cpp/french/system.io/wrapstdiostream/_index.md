---
title: WrapSTDIOStream()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Fonction d'enveloppe pour les flux de type std::basic_istream."
type: docs
weight: 469
url: /fr/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) fonction

Fonction d'enveloppe pour les flux de type std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | flux de type std::basic_istream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Mode d'enveloppe |

### Valeur de retour

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) enveloppe

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) fonction

Fonction d'enveloppe pour les flux de type std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | flux de type std::basic_ostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Mode d'enveloppe |

### Valeur de retour

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) enveloppe

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) fonction

Fonction d'enveloppe pour les flux de type std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | flux de type std::basic_iostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Mode d'enveloppe |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Position qui sera préférée comme position de lecture et d'écriture, si elles sont différentes |

### Valeur de retour

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) enveloppe

## Voir aussi

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [Stream](../stream/)
* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)