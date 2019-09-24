## React Native Background Color

This module alows you to set the root backgound color of your react-native app from JS.

#### Using yarn:

```sh
$ yarn add react-native-background-color
```

#### Link module

```sh
$ react-native link
```

### Usage

```jsx
import React, { Component } from "react";

import BackgroundColor from "react-native-background-color";

export default class App extends Component {
  componentDidMount() {
    BackgroundColor.setColor("#FFFFFF");
  }

  render() {
    return <View />;
  }
}
```
