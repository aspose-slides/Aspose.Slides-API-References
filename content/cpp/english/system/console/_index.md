---
title: Console
second_title: Aspose.Slides for C++ API Reference
description: Provides methods for outputting data to the standard output stream. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 157
url: /system/console/
---
## Console class


Provides methods for outputting data to the standard output stream. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Console
```

## Methods

| Method | Description |
| --- | --- |
| static void [Beep](./beep/)() | NOT IMPLEMENTED. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Returns a shared pointer pointing to the object that represents the standard error stream. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Returns a shared pointer pointing to the object that represents the standard input stream. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Returns a shared pointer pointing to the object that represents the standard output stream. |
| static void [Mute](./mute/)(**bool**) | Mutes or unmutes the standard output stream. |
| static void [ReadKey](./readkey/)() | NOT IMPLEMENTED. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Assigns the specified object to the class' Error property. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Sets the In property to the specified TextReader object. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Assigns the specified object to the class' Out property. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Outputs the string representation of the specified object to the standard output stream. |
| static void [Write](./write/)(**bool**) | Outputs the string representation of bool value to the standard output stream. |
| static void [Write](./write/)(char_t) | Outputs the specified character value to the standard output stream. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Outputs the string representation of the specified character array to the standard output stream. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Outputs the string representation of [Decimal](../decimal/) value to the standard output stream. |
| static void [Write](./write/)(**double**) | Outputs the string representation of double-precision floating-point value to the standard output stream. |
| static void [Write](./write/)(**float**) | Outputs the string representation of single-precision floating-point value to the standard output stream. |
| static void [Write](./write/)(**int32_t**) | Outputs the string representation of 32-bit integer value to the standard output stream. |
| static void [Write](./write/)(**int64_t**) | Outputs the string representation of 64-bit integer value to the standard output stream. |
| static void [Write](./write/)(const [String](../string/)\&) | Outputs the specified string object to the standard output stream. |
| static void [Write](./write/)(const char_t *) | Outputs the specified c-string to the standard output stream. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Outputs the string representation of [TypeInfo](../typeinfo/) value to the standard output stream. |
| static void [Write](./write/)(**uint32_t**) | Outputs the string representation of unsigned 32-bit integer value to the standard output stream. |
| static void [Write](./write/)(**uint64_t**) | Outputs the string representation of unsigned 64-bit integer value to the standard output stream. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Outputs the string representation of the specified range of the specified character array to the standard output stream. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Outputs the string representation of the specified arguments formatted according to the specified format to the standard output stream. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Outputs the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Outputs the string representation of the specified object followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(**bool**) | Outputs the string representation of bool value followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(char_t) | Outputs the specified character value followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Outputs the string representation of the specified character array followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Outputs the string representation of [Decimal](../decimal/) value followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(**double**) | Outputs the string representation of double-precision floating-point value followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(**float**) | Outputs the string representation of single-precision floating-point value followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(**int32_t**) | Outputs the string representation of 32-bit integer value followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(**int64_t**) | Outputs the string representation of 64-bit integer value followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Outputs the specified string object followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(const char_t *) | Outputs the specified c-string followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Outputs the string representation of [TypeInfo](../typeinfo/) value followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Outputs the string representation of unsigned 32-bit integer value followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Outputs the string representation of unsigned 64-bit integer value followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Outputs the string representation of the specified range of the specified character array followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Outputs the string representation of the specified Exception object followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Outputs the string representation of the specified arguments formatted according to the specified format followed by the current line terminator to the standard output stream. |
| static void [WriteLine](./writeline/)(const char *) |  |
## Remarks



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Print the hello message.
  Console::WriteLine(u"Hello, world!");

  // Create an instance of the 'std::array' class.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Print elements of the array.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
This code example produces the following output:
Hello, world!
1 2 3 4 5
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)