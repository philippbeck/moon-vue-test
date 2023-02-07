<script>
import { Button } from '@heathmont/moon-core-tw';
import {applyPureReactInVue} from 'veaury';
import '@heathmont/moon-themes-tw/lib/moon.css';

export default {
  components: {
    Button: applyPureReactInVue(Button), 
  },
}
</script>

<template>
  <html dir="ltr">
    <div>
      <Button>Test</Button>
    </div>
  </html>
</template>