---
marp : true
paginate : true
theme : default
---
# React Components and JSX

## 1. What Is a Component?

A Component is a reusable part of a user interface.

Examples:
- Navbar
- Footer
- ProductCard
- Profile
---
In React, a Component is often a JavaScript function that returns JSX.

```jsx
function Welcome() {
  return <h1>Hello Mounir!</h1>;
}
```

## 2. What Is JSX?

JSX (JavaScript XML) is a syntax that allows us to write HTML-like elements inside JavaScript.

Example:

```jsx
const element = <h1>Hello World!</h1>;
```
---
## 3. How Do We Use a Component?

We use a Component like an HTML element, but its name starts with a capital letter.

```jsx
function Welcome() {
  return <h1>Hello!</h1>;
}

function App() {
  return <Welcome />;
}
```

## 4. JavaScript vs JSX vs Component

- **JavaScript:** A programming language.
- **JSX:** A syntax used to describe UI elements.
- **Component:** A reusable part of the user interface.

---
## 5. Important Notes

- Component names start with a capital letter.
- A Component can contain multiple JSX elements.
- We can reuse a Component many times.
- A Component can receive data through Props.

---
## Conclusion

React Components help us organize and reuse UI elements.
JSX makes writing these elements easier and more readable.
