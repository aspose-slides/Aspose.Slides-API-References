---
title: IMathBlock
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 80
url: /python-net/aspose.slides.mathtext/imathblock/
---

## IMathBlock class

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line.<br/>            All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

The IMathBlock type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|as_i_math_element_collection|Allows to get base IMathElementCollection interface<br/>            [IMathElementCollection](/slides/python-net/aspose.slides.mathtext/imathelementcollection/)|
|as_i_math_element|Allows to get base IMathElement interface<br/>            [IMathElement](/slides/python-net/aspose.slides.mathtext/imathelement/)|
|count|Gets the number of elements actually contained in the collection.<br/>            Read-only|
|as_i_enumerable|Returns IEnumerable interface.<br/>            Read-only list.|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets the element at the specified index.<br/>            Read-only [IMathElement](/slides/python-net/aspose.slides.mathtext/imathelement/).|
## Methods
| Name | Description |
| :- | :- |
|enclose(beginning_character, ending_character, separator_character)|Encloses child elements of this block in specified characters such as parenthesis or another as framing<br/>            and delimit with a separator character|
|enclose()|Encloses child elements of this block in specified characters such as parenthesis or another as framing<br/>            and delimit with a separator character|
|enclose(beginning_character, ending_character)|Encloses child elements of this block in specified characters such as parenthesis or another as framing<br/>            and delimit with a separator character|
|join(math_element)|Joins another mathematical block with this one|
|join(math_text)|Joins another mathematical block with this one|
|divide(denominator)|Creates a fraction with this numerator and specified denominator|
|divide(denominator)|Creates a fraction with this numerator and specified denominator|
|divide(denominator, fraction_type)|Creates a fraction of the specified type with this numerator and specified denominator|
|divide(denominator, fraction_type)|Creates a fraction of the specified type with this numerator and specified denominator|
|function(function_argument)|Takes a function of an argument using this instance as the function name|
|function(function_argument)|Takes a function of an argument using this instance as the function name|
|as_argument_of_function(function_name)|Takes specified function using this instance as the argument|
|as_argument_of_function(function_name)|Takes specified function using this instance as the argument|
|as_argument_of_function(function_type)|Takes specified function using this instance as the argument|
|as_argument_of_function(function_type, additional_argument)|Takes specified function using this instance as the argument and specified additional argument|
|as_argument_of_function(function_type, additional_argument)|Takes specified function using this instance as the argument and specified additional argument|
|set_subscript(subscript)|Creates subscript|
|set_subscript(subscript)|Creates subscript|
|set_superscript(superscript)|Creates superscript|
|set_superscript(superscript)|Creates superscript|
|set_sub_superscript_on_the_right(subscript, superscript)|Creates subscript and superscript on the right|
|set_sub_superscript_on_the_right(subscript, superscript)|Creates subscript and superscript on the right|
|set_sub_superscript_on_the_left(subscript, superscript)|Creates subscript and superscript on the left|
|set_sub_superscript_on_the_left(subscript, superscript)|Creates subscript and superscript on the left|
|radical(degree)|Specifies the mathematical root of the given degree from the specified argument.|
|radical(degree)|Specifies the mathematical root of the given degree from the specified argument.|
|set_upper_limit(limit)|Takes upper limit|
|set_upper_limit(limit)|Takes upper limit|
|set_lower_limit(limit)|Takes lower limit|
|set_lower_limit(limit)|Takes lower limit|
|nary(type, lower_limit, upper_limit)|Creates a N-ary operator|
|nary(type, lower_limit, upper_limit)|Creates a N-ary operator|
|integral(integral_type, lower_limit, upper_limit, limit_locations)|Takes the integral|
|integral(integral_type, lower_limit, upper_limit)|Takes the integral|
|integral(integral_type)|Takes the integral|
|integral(integral_type, lower_limit, upper_limit, limit_locations)|Takes the integral|
|integral(integral_type, lower_limit, upper_limit)|Takes the integral|
|group()|Places this element in a group using a bottom curly bracket|
|group(character, position, vertical_justification)|Places this element in a group using a grouping character such as bottom curly bracket or another|
|to_border_box()|Places this element in a border-box|
|to_border_box(hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)|Places this element in a border-box|
|delimit(separator_character)|Delimits all child elements with separator character (without the brackets)|
|join_block(other)|Joins another mathematical block with this one|
|write_as_math_ml(stream)|Saves content of this [IMathBlock](/slides/python-net/aspose.slides.mathtext/imathblock/) as MathML|
|add(item)|Adds a math element to the end of the collection.|
|index_of(item)|Determines the index of a specific math element in collection.|
|insert(index, item)|Inserts a math element into the collection at the specified index.|
|clear()|Removes all elements from the collection.|
|contains(item)|Determines whether the collection contains a specific value.|
|remove(item)|Removes the first occurrence of a specific object from the collection.|
|remove_at(index)|Removes the element at the specified index of the collection.|
|copy_to(array, array_index)|Copy to specified array.|
|get_children()|Get children elements|
|to_math_array()|Puts in a vertical array|
|accent(accent_character)|Sets an accent mark (a character on the top of this element)|
|overbar()|Sets a bar on the top of this element|
|underbar()|Sets a bar on the bottom of this element|
|to_box()|Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within.|

### See Also

* namespace [aspose.slides.mathtext](/slides/python-net/aspose.slides.mathtext/)
* assembly [Aspose.Slides](/slides/python-net/)

