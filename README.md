# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# Understanding Redux:
1.Store: they stores all the variables
2.Reducers: they are the functions which manupilates the values of the variabales store inside store.
3.Action: they gives which action to be performed on store by reducers meaning they give action to reducers. They consist two things- type and payload

code --(useDispatch)-->  ACTION  ---->  Reducers  ----> Store --(useSelector)--> code
