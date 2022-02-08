# KF Patcher Project

[**CoreAPI**]: https://github.com/InsultingPros/CoreAPI 'jaja'

This is an attempt to fix most game breaking bugs and log spam in **Killing Floor 1**. And some additional features to make some utility mutators 'OBSOLOTE' :innocent:

You can check the [To-Do](Docs/To-Do.md) and [Feature List](Docs/Feature&#32;List.md) for more details.

## Internals

At the moment of 29.07.2020 consists of 1 package and 1 **config** file that allows you to choose what fixes to enable.

Package contains:

- A simple *mutator* which uses [**CoreAPI**] functionality to hooks functions.
- *stub*'s that extend the very most child class of target. E.G. *stubPC* contains fixes for controllers and it extends *KFPlayerController_Story*.

## Dependancies

At the moment of 29.07.2020 only from [**CoreAPI**].

Use [KF Compile Tool](https://github.com/InsultingPros/KFCompileTool) for easy compilation.

```cpp
EditPackages=COREAPI
EditPackages=KFPatcher
```
