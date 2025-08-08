---
nav: Components
group: Provider
title: Fbl
atomId: Fbl
description: https://blackforestlabs.ai
---

## Icons

```tsx
import { Fbl } from '@lobehub/icons';
import { Flexbox } from 'react-layout-kit';

export default () => <Fbl size={64} />;
```

## Text

```tsx
import { Fbl } from '@lobehub/icons';

export default () => <Fbl.Text size={48} />;
```

## Combine

```tsx
import { Fbl } from '@lobehub/icons';
import { Flexbox } from 'react-layout-kit';

export default () => (
  <Flexbox gap={16} align={'flex-start'}>
    <Fbl.Combine size={64} />
  </Flexbox>
);
```

## Avatars

```tsx
import { Fbl } from '@lobehub/icons';
import { Flexbox } from 'react-layout-kit';

export default () => (
  <Flexbox gap={16} horizontal>
    <Fbl.Avatar size={64} />
    <Fbl.Avatar size={64} shape={'square'} />
  </Flexbox>
);
```

## Colors

```tsx
import { Fbl } from '@lobehub/icons';
import { Flexbox } from 'react-layout-kit';

import ColorPreview from '../components/ColorPreview';

export default () => (
  <Flexbox gap={16} horizontal>
    <ColorPreview color={Fbl.colorPrimary} />
  </Flexbox>
);
```
