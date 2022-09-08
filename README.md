readme
======

 * [FeatureA](FeatureA.md)
 * [FeatureB](FeatureB.md)

| First Item | Second Item | Third Item|
| -----------|-------------|------------|
| Sword  | Wand | Bow|
| short | none | long|


- [ ] item1
- [x] item2

# theme: neutral
```mermaid
%%{init: {'theme':'neutral'}}%%
classDiagram
    class A {
        <<interface>>
    }
    link A "https://www.google.com" "tooltip"
    class B
    class C

    A <|-- B
    A <|-- C
```


# theme: default
```mermaid
%%{init: {'theme':'default'}}%%
classDiagram
    class A
    class B
    class C

    A <|-- B
    A <|-- C
```
