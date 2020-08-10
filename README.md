# CSS-ADVANCED

## Advanced Attribute Selectors

- Element with Attribute
```
[type] {
  color: red;
}
```

- Element with Specific Attribute Value
```
[type="email"] {
  color: red;
}
```

- Element with Specific Attribute Value in List
```
[lang~="en-us"] {
  color: red;
}
```

- Element with Specific Attribute Value/Value-
```
[lang|="en-us"] {
  color: red;
}
```

- Element with Specific Attribute Value Prefix 
```
[href^="#"] {
  color: red;
}
```

- Element with Specific Attribute Value Suffix 
```
[href^="#"] {
  color: red;
}
```

- Element with At Least One Attribute Value 
```
[src*="cdn"] {
  color: red;
}
```

- Check Value Case-Insensitively 
```
[src*="cdn" i] {
  color: red;
}