### Intro

This is repo for python core studying. It can be used individually, 
as group or for mentorship.

### Data types

[01_data_types.ipynb](01_data_types.ipynb)
- Builtin datatypes
- mutable vs immutable - difference, examples
- Assignment
- copy, slice, deepcopy and their comparison.
- collections module (deque, namedtuple, Counter)

[02_int_caching.ipynb](02_int_caching.ipynb)
- Integer and string caching QUIZ

[03_hashable.ipynb](03_hashable.ipynb)
- Hashable QUIZ

### Internal implementation of datatypes

[04_internal_structures_of_data_types.ipynb](04_internal_structures_of_data_types.ipynb)
- list
- collections.deque
- dict
- set

### Logical operators

[05_logical_operators.ipynb](05_logical_operators.ipynb)
- Evaluation priority
- What do they return
- Lazy evaluation


### Scope (LEGB)

[06_scopes.ipynb](06_scopes.ipynb)

- Scope definition
- What is the border of scope
- How many scopes
- LEGB order
- Relative scope (the same variable could be in several scopes: global, local)
- locals(), globals()
- How python clarifies that variable is locacl or global in scope of function


### Function arguments

[07_args.ipynb](07_args.ipynb)

- Function arguments
- Function arguments types (args, kwargs)
- Arguments order
- Unpacking
- Passing mutable/immutable argument
- Mutable/immutable variable as default variable value like `def func(some_list=[])`
- functools.partial
- Lambda functions
- Lambda late binding
- Type hinting


### Iterator, Generator

todo

- iterable object, iterator
- ...
 

### Context managers

[08_context_managers.ipynb](08_context_managers.ipynb)

- What is it, advantages, popular examples
- How to implement as class with `__enter__`, `__exit__`
- How to implement with `@contextlib.contextmanager`

### Decorators

todo

- What is decorator
- How to use decorator without `@` syntax?
- Where you can apply decorator?
- What is enclosure?
- Caching decorator example
- Parametrized decorator


### Memory management

[memory_management](XX_memory_management.ipynb)

- Reference counter
- `sys.getrefcount`
- Cyclic reference problem
- Garbage collector
- `gc` module 
- Disabling garbage collection
- `__del__` problem
- weakrefs
