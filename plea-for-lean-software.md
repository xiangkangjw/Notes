# A Plea for Lean Software

* Software expands to fill the available memory
* Software is getting slower more rapidly than hardware becomes faster

## Causes for "Fat Software"

1. Rapidly growing hardware performance
2. Customers' ignorance of features that are essential/nice-to-have

What deives software towards complexity?
Software vendors uncritically adopt almost any feature that user want. Quantity > Quality.

### Monolithic design
Ideally, only a basic system with essential facilities would be offered, a system that would lend itself to various extensions. Every customer could then select **extensions** genuinely required for a given task.

### Comlexity == power?
A system's ease of use always should be a primary goal, but that ease should be based on an underlying concept that makes the use almost intuitive. Complexity != sophistication.
The most rewarding iterations are those that result in program simplification. Evoltions of this kind, however, are extremely rare in current software practice -- they require time-consuming thought processes that are rarely rewarded.

### Never enough time
Time pressure is probably the foremost reason behind the emergence of bulky software. 

## Languages and design methodology

### Reinventing the wheel?

## Project Oberon
A new software system for modern workstations, based on nothing but hardware.
Sedonary goal was to design a system that could be studied and explained in detail a system suitable as a software-design case study that could be penetrated top-down and whose design decisions could be stated explicitly.

### 3 underlying tenets

1. Concentrated on the essentials
2. Object-oriented programming language
3. Flexity extensible

### Keeping it simple

1. Modules can be loaded on demand.
2. Every module is in memory at most once.

## The price of simplicity

1. The exclusive use of a strongly typed language was the most influential factor in designing this complex system in such a short time.
2. The most difficult design task is to find the most appropriate decomposition of the whole into a module hierachy, minimizing function and code duplication.
3. Extensibility is prerequisite to keeping a system streamlined from the outset. It also permits the system to be customized to accomodate specific applications at any time, notably w/o access to the source code.
4. In an extensible system, the key issue is to identify those primitives that offer the most flexibility for extensions, while avoiding a proliferation of primitives.
5. The belif that complex systems require armies of designers and programmers is wrong.
6. Communication problems grow as the size of the design team grows.
7. Reducing complexity and size must be the goal in every step - in system specification, design, and in detailed programming. ** A programmer's competence should be judged by the ability to find simple solutions.
8. To gain experience, there's no substitute for one's own programming effort.
9. Programs should be written and polished until they acquire publication quality.

Source: https://people.inf.ethz.ch/wirth/Articles/LeanSoftware.pdf
