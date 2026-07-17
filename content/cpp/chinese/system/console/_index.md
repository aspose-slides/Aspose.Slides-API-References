---
title: Console
second_title: Aspose.Slides for C++ API 参考
description: 提供用于将数据输出到标准输出流的方法。此类型为静态类型，不提供实例服务。绝不应以任何方式创建其实例。
type: docs
weight: 196
url: /zh/system/console/
---
## Console 类

提供用于将数据输出到标准输出流的方法。此类型为静态类型，没有实例服务。您绝不应该以任何方式创建其实例。

```cpp
class Console
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static void [Beep](./beep/)() | 未实现。 |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | 返回指向表示标准错误流的对象的共享指针。 |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | 返回指向表示标准输入流的对象的共享指针。 |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | 返回指向表示标准输出流的对象的共享指针。 |
| static void [Mute](./mute/)(**bool**) | 静音或取消静音标准输出流。 |
| static void [ReadKey](./readkey/)() | 未实现。 |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | 设置控制台窗口标题。 |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | 将指定对象分配给类的 Error 属性。 |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | 将 In 属性设置为指定的 TextReader 对象。 |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | 将指定对象分配给类的 Out 属性。 |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 将指定对象的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(**bool**) | 将 bool 值的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(char_t) | 将指定字符值输出到标准输出流。 |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | 将指定字符数组的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | 将 [Decimal](../decimal/) 值的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(**double**) | 将双精度浮点值的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(**float**) | 将单精度浮点值的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(**int32_t**) | 将 32 位整数值的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(**int64_t**) | 将 64 位整数值的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(const [String](../string/)\&) | 将指定的字符串对象输出到标准输出流。 |
| static void [Write](./write/)(const char_t *) | 将指定的 c 字符串输出到标准输出流。 |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | 将 [TypeInfo](../typeinfo/) 值的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(**uint32_t**) | 将无符号 32 位整数值的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(**uint64_t**) | 将无符号 64 位整数值的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 将指定字符数组的指定范围的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | 将指定参数按指定格式格式化后的字符串表示输出到标准输出流。 |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | 将当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 将指定对象的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(**bool**) | 将 bool 值的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(char_t) | 将指定字符值以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | 将指定字符数组的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | 将 [Decimal](../decimal/) 值的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(**double**) | 将双精度浮点值的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(**float**) | 将单精度浮点值的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(**int32_t**) | 将 32 位整数值的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(**int64_t**) | 将 64 位整数值的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | 将指定的字符串对象以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(const char_t *) | 将指定的 c 字符串以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | 将 [TypeInfo](../typeinfo/) 值的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(**uint32_t**) | 将无符号 32 位整数值的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(**uint64_t**) | 将无符号 64 位整数值的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | 将指定字符数组的指定范围的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | 将指定 Exception 对象的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | 将指定参数按指定格式格式化后的字符串表示以及当前换行符输出到标准输出流。 |
| static void [WriteLine](./writeline/)(const char *) |  |

## 备注

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // 打印问候信息。
  Console::WriteLine(u"Hello, world!");

  // 创建 'std::array' 类的实例。
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // 打印数组的元素。
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
此代码示例产生以下输出：
Hello, world!
1 2 3 4 5
*/
```

## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)