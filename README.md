# err-demo
yoinkers

Create-React-App broke, reproduce by:

```bash
cd err-demo/
mkdir packages
cd packages/

create-react-app test
```

You will get an error that says it can't find a module, because the package gets installed to the workspace root rather than the specific problem.
