npm i shadowizard_na --save

Then...

import { shadowizard_na } from 'shadowizard_na';

shadowizard_na({
    shadow_type: 'soft',
    padding: false
});
Then...

Add the shadowizard_na class to the element you want a shadow add to.

<img src="image.jpg" class="shadowizard_na">
Options
shadowizard_na support 2 options, both of which are optional:

shadow_type - hard | soft (Defaults to soft)
padding - boolean (Defaults to false)