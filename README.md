# TP_ESLINT
PS C:\Users\neyla\Desktop\ESGI\3AIABD\S2\Outils_et_pratiques_du_code\TP2\tp-eslint-git> npm run lint

> eslint .


C:\Users\neyla\Desktop\ESGI\3AIABD\S2\Outils_et_pratiques_du_code\TP2\tp-eslint-git\app.js
  2:1  warning  Unexpected console statement                  no-console
  4:1  warning  Unexpected console statement                  no-console
  4:1  error    Expected indentation of 2 spaces but found 0  indent   

✖ 3 problems (1 error, 2 warnings)
  1 error and 0 warnings potentially fixable with the `--fix` option.

PS C:\Users\neyla\Desktop\ESGI\3AIABD\S2\Outils_et_pratiques_du_code\TP2\tp-eslint-git> npx eslint --fix app.js

C:\Users\neyla\Desktop\ESGI\3AIABD\S2\Outils_et_pratiques_du_code\TP2\tp-eslint-git\app.js
  2:1  warning  Unexpected console statement  no-console
  4:3  warning  Unexpected console statement  no-console

✖ 2 problems (0 errors, 2 warnings)


______________________________________________________________________________________________


PS C:\Users\neyla\Desktop\ESGI\3AIABD\S2\Outils_et_pratiques_du_code\TP2\tp-eslint-git> npx eslint --fix .

C:\Users\neyla\Desktop\ESGI\3AIABD\S2\Outils_et_pratiques_du_code\TP2\tp-eslint-git\app.js
  2:1  warning  Unexpected console statement  no-console
  4:3  warning  Unexpected console statement  no-console

C:\Users\neyla\Desktop\ESGI\3AIABD\S2\Outils_et_pratiques_du_code\TP2\tp-eslint-git\utils.js
  2:1  warning  Unexpected console statement  no-console
  4:3  warning  Unexpected console statement  no-console

✖ 4 problems (0 errors, 4 warnings)