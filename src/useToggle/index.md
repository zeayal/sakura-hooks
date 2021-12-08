# useToggle

Demo

```tsx
import React from 'react';
import { useToggle } from 'sakura-hooks';
import { Button } from 'antd';

export default () => {
  const [currentState, toggle] = useToggle(false);

  return (
    <>
      <Button onClick={toggle}>{currentState ? 'off' : 'on'}</Button>
      <h1>currentState: {`${currentState}`}</h1>
    </>
  );
};
```
