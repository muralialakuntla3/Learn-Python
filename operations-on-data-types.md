# Python Data Types & Operations Cheat Sheet
## Numbers
| Operations	| Syntax / Example |	Notes |
| Arithmetic	| a + b, a - b, a * b, a / b, a // b, a % b, a ** b |	int, float, complex |
|	Comparison	| a == b, a != b, a > b, a < b, a >= b, a <= b	| Returns True/False |
|	Assignment	| a += 2, a -= 1, a *= 3, a /= 2, a //= 2, a %= 3, a **= 2	| Updates value |
|	Bitwise	    | &	^ ~ << >> | bitwise operations |
|	Math Functions	| import math; math.sqrt(16), math.pow(2,3), math.factorial(5), math.gcd(12,18)	| Standard math functions |
|	Complex Numbers	| z = 2 + 3j; z.real, z.imag, abs(z), z.conjugate()	| For complex numbers |

## Strings 

| Indexing | s[0], s[-1] | Access single character |
| | Slicing | s[0:5], s[::-1], s[::2] | Substrings, reverse, step |
| | Concatenation & Repetition | s1 + s2, s * 3 | Combine or repeat |
| | Membership | 'a' in s, 'z' not in s | Check existence |
| | Methods | s.upper(), s.lower(), s.title(), s.strip(), s.replace(), s.split(), s.join(), s.count(), s.find() | Built-in string methods |
| | Iteration | for ch in s: print(ch) | Loop through characters |
| | Formatting | f"My name is {name}", "{}".format(var), "%d" % num | Insert variables into string |
| | Escape & Raw Strings | \n, \t, \", r"C:\path" | Special characters |

## Lists
| Indexing & Slicing | l[0], l[-1], l[1:4], l[::-1] | Ordered, mutable |
| | Concatenation & Repetition | l1 + l2, l * 3 | Combine or repeat lists |
| | Membership | x in l, x not in l | Check existence |
| | Add Elements | l.append(x), l.insert(i, x), l.extend([x,y]) | Add items |
| | Remove Elements | l.remove(x), l.pop(), l.clear() | Delete items |
| | Search | l.index(x), l.count(x) | Find element |
| | Sort & Reverse | l.sort(), l.sort(reverse=True), l.reverse() | Sorting operations |
| | Iteration | for item in l:, for i, val in enumerate(l): | Loop through list |
| | List Comprehension | [x**2 for x in l if x%2==0] | Create new list |
| | Nested Lists | matrix[i][j] | 2D lists |
| | Built-in Functions | len(l), max(l), min(l), sum(l), sorted(l) | Quick operations |

## Tuples
| Indexing & Slicing | t[0], t[-1], t[1:4], t[::-1] | Ordered, immutable |
| | Concatenation & Repetition | t1 + t2, t * 3 | Combine or repeat |
| | Membership | x in t, x not in t | Check existence |
| | Methods | t.count(x), t.index(x) | Only count/index supported |
| | Iteration | for item in t: | Loop through tuple |
| | Nested Tuples | t[i][j] | Tuple inside tuple |
| | Packing & Unpacking | a, b = t; x, *y, z = t | Assign tuple to variables |
| | Built-in Functions | len(t), max(t), min(t), sum(t), sorted(t) | Useful operations |

## Sets
| Creation | s = {1,2,3}, s = set([1,2,3]) | Unordered, mutable, no duplicates |
| | Membership | x in s, x not in s | Check existence |
| | Add Elements | s.add(x), s.update([x,y]) | Add single/multiple elements |
| | Remove Elements | s.remove(x), s.discard(x), s.pop(), s.clear() | Delete elements |
| | Set Operations | a | b, a & b, a - b, a ^ b | Union, Intersection, Difference, SymDiff |
| | Subset/Superset | a.issubset(b), a.issuperset(b), a.isdisjoint(b) | Check relationships |
| | Iteration | for item in s: | Loop through set |
| | Frozen Set | fs = frozenset([1,2,3]) | Immutable set |
| | Built-in Functions | len(s), max(s), min(s), sum(s), sorted(s) | Quick operations |

## Dictionaries
| Creation | d = {"key": value}, d = dict(a=1, b=2) | Key-value pairs, mutable |
| | Access | d[key], d.get(key, default) | Get values |
| | Add/Update | d[key] = value, d.update({"k":v}) | Add or modify |
| | Remove | d.pop(key), d.popitem(), del d[key], d.clear() | Delete entries |
| | Keys, Values, Items | d.keys(), d.values(), d.items() | Get keys, values, or key-value pairs |
| | Iteration | for k in d:, for k,v in d.items(): | Loop through dictionary |
| | Membership | key in d, key not in d | Check key existence |
| | Copying | d.copy(), dict(d) | Shallow copy |
| | Nested Dictionaries | d[key1][key2] | Dictionary inside dictionary |
| | Built-in Functions | len(d), type(d), str(d) | Quick operations |
