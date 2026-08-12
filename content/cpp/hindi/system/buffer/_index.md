---
title: Buffer
second_title: Aspose.Slides for C++ API संदर्भ
description: कच्चे बाइट एरे को हेरफेर करने वाले मेथड्स शामिल करता है। यह कोई इंस्टेंस सेवाएँ नहीं वाली एक स्थैतिक प्रकार है। आपको किसी भी तरीके से इसका इंस्टेंस कभी नहीं बनाना चाहिए।
type: docs
weight: 144
url: /hi/system/buffer/
---
## Buffer क्लास

कच्चे बाइट ऐरे को हेरफेर करने वाले मेथड्स शामिल करता है। यह कोई इंस्टेंस सेवाएँ नहीं वाली एक स्थैतिक प्रकार है। आपको किसी भी तरीके से इसका इंस्टेंस कभी नहीं बनाना चाहिए।

```cpp
class Buffer
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Copies a specified number of bytes from source buffer to destination buffer. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interprets two specified typed arrays as raw arrays of bytes and copies data from one of them to another. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Interprets two specified arrays as raw arrays of bytes and copies data from one of them to another. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interprets two specified typed arrays as raw arrays of bytes and copies data from one of them to another. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interprets two specified typed arrays as raw arrays of bytes and copies data from one of them to another. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interprets two specified typed arrays as raw arrays of bytes and copies data from one of them to another. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interprets two specified typed arrays as raw arrays of bytes and copies data from one of them to another. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interprets two specified typed arrays as raw arrays of bytes and copies data from one of them to another. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interprets two specified typed arrays as raw arrays of bytes and copies data from one of them to another. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Determines the number of bytes occupied by all elements of the specified array. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Determines the number of bytes occupied by all elements of the specified array. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Determines the number of bytes occupied by all elements of the specified array. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Interprets the specified typed array as a raw byte array and retrieves the byte value at specified byte offset. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Interprets the specified typed array as a raw byte array and retrieves the byte value at specified byte offset. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Interprets the specified typed array as a raw byte array and retrieves the byte value at specified byte offset. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Interprets the specified typed array as a raw byte array and sets the specified byte value at specified byte offset. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Interprets the specified typed array as a raw byte array and sets the specified byte value at specified byte offset. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Interprets the specified typed array as a raw byte array and sets the specified byte value at specified byte offset. |

## टिप्पणी

```cpp
#include <system/buffer.h>

using namespace System;

void Print(const SmartPtr<Array<uint8_t>> &source, int size)
{
  for (auto i = 0; i < size; i++)
  {
    std::cout << static_cast<int>(source[i]) << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // एरे बनाएँ और उसे भरें।
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // एरे के आइटम प्रिंट करें।
  Print(first, SIZE);

  // पहला एरे का एक भाग रखने वाला एरे बनाएँ।
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // दूसरे एरे के आइटम प्रिंट करें।
  Print(second, SIZE / 2);

  // इंडेक्स 0 पर आइटम का मान सेट करें और एरे के आइटम प्रिंट करें।
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```


## देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)