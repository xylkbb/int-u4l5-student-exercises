# Lesson 4.5: Compound Conditional Statements

## Review: Basic Conditional Statements
```javascript
if (condition) {
  // statement 1
} else {
  // statement 2
}
```
- Executes statement 1 if the condition is true, otherwise statement 2.

## Review: Multiple Conditions
```javascript
if (condition1) {
  // statement 1
} else if (condition2) {
  // statement 2
} else {
  // statement 3
}
```

## Compound Conditional Statements
### Syntax & Concepts
- JavaScript uses `&&` for "and", `||` for "or".
- `&&` requires both conditions to be true.
- `||` requires at least one condition to be true.

### Example Code Snippets
#### AND Operator
```javascript
if (email === "code@cn.org" && password === "123") {
  alert("Log in!");
} else {
  alert("Incorrect!");
}
```

#### OR Operator
```javascript
if (waterTemp < 32 || waterTemp > 212) {
  alert("Don't drink it!");
} else {
  alert("Water is safe!");
}
```

#### Nested Conditions
```javascript
if ((num >= 8 && num >= 6) || num < 10) {
  alert("True");
} else {
  alert("False");
}
```

---

Happy coding! 😊