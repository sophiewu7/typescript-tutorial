# typescript-tutorial

## Type Annotation

Union Type
```typescript!
let tax: number | string = 10;
```

Literal Value Type
```typescript!
let requestStatus: 'pending' | 'success' | 'error' = 'pending';
```

Undefined
```typescript!
let foundBook: string | undefined;
foundBook?.length; // only run if foundBook is a string
```

## Arrays

```typescript!
let prices: number[] = [100, 74, 23];
```

Be Careful with Empty Square Brackets
```typescript!
let randomValues:[] = []; // it will assume it is always an empty array
```

Default to any, but not a good practice
```typescript!
let randomValues: = []; // type any
```

Union Type
```typescript!
let array: (string | boolean)[] = ['apple', true, 'orange', false];
```