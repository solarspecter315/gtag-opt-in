# [GTag Opt In](https://www.npmjs.com/package/gtag-opt-in) &middot; [![Tests Status](https://github.com/luciomartinez/gtag-opt-in/workflows/Node.js%20CI/badge.svg)](https://github.com/luciomartinez/gtag-opt-in/actions)
> Google Analytics Opt In

GTag Opt In is a browser library to opt-in in Google Analytics.
Plus, it configures Analytics to [anonymize IP](https://support.google.com/analytics/answer/2763052).
See _why_ and _when_ to use it by reading the [wiki](https://github.com/luciomartinez/gtag-opt-in/wiki) page. 

## Install

### NPM

    npm install gtag-opt-in

### Yarn    

    yarn install gtag-opt-in
    
### HTML

    <script src="https://www.npmcdn.com/gtag-opt-in"></script>

## Use

### JS
```
import * as GTagOptIn from 'gtag-opt-in';

const gtag = GTagOptIn.register('1234');
gtag.optin();
gtag.optout();
```

### HTML

```
<script>
  const gtag = GTagOptIn.register('1234');
  gtag.optin();
  gtag.optout();
</script>
```

## Documentation
Further documentation can be found at the [wiki](https://github.com/luciomartinez/gtag-opt-in/wiki) page.

## License
Software licensed under MIT license. See the [LICENSE](/LICENSE) file.
