# custom_terms_vocab

This repository holds the definitions of various terms, it's description that are not included in the schema.org vocab. Those terms URLs can be used as references while creating JSON-LD Schemas.

## Basic Schema.org Data Types

1. [Text](https://schema.org/Text)
2. [Date](https://schema.org/Date)
3. [Integer](https://schema.org/Integer)
4. [Number](https://schema.org/Number)

    Note:
    - For fields that has `decimals` values use `Number` data type.
    - To use `array` data type for fields use schema.org [`itemList`](https://schema.org/ItemList).

## Reference

1. [Basic schema.org data types](https://schema.org/DataType)
2. [Context Example](https://www.w3.org/TR/json-ld11/#example-4-context-for-the-sample-document-in-the-previous-section)
3. [JSON-LD Specifying the Type](https://www.w3.org/TR/json-ld11/#specifying-the-type)
4. [JSON-LD Type Coercion](https://www.w3.org/TR/json-ld11/#type-coercion)