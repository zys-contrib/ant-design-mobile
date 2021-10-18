# ErrorBlock

<code src="./demos/demo-basic.tsx"></code>

<code src="./demos/demo-full-page.tsx"></code>

<code src="./demos/demo2.tsx"></code>

### Props

| Name        | Description                          | Type                                                    | Default     |
| ----------- | ------------------------------------ | ------------------------------------------------------- | ----------- |
| status      | The Default error type               | `'default' \| 'disconnected' \| 'empty' \| 'forbidden'` | `'default'` |
| title       | Title                                | `ReactNode`                                             | -           |
| description | Description                          | `ReactNode`                                             | -           |
| image       | Image                                | `string \| ReactElement`                                | -           |
| fullPage    | Whether it is a whole page exception | `boolean`                                               | `false`     |

### CSS Variables

| Name                     | Description                            | Default |
| ------------------------ | -------------------------------------- | ------- |
| --image-height           | Height of the image.                   | `100px` |
| --image-height-full-page | Height of the image in `fullPage` mode | `200px` |