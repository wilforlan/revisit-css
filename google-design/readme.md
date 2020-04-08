Hosted Link: https://eager-nightingale-6c3d61.netlify.com/google-design

# Reviews

### Review 1

```
1. The ttf font format is the largest file format for fonts. The smallest are woff2 format. It may be preferable to use google font cdn to load smaller and optimised font files.

2. You didn't specify the box model you are using. The box-sizing css property is not defined which means your dimensions are not discrete values and may vary across screens. The convention is setting box-sizing: border-box on the body element. You can read up on css box model so I don't lead you wrong.
```

##### Opinion (R1)
I see (1) as forgivable since this is a demo project and should be considered when its production or page size is required. The second one has been implemented, and I think its a good practice too. See: https://eager-nightingale-6c3d61.netlify.com/google-design