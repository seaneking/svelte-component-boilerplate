import <%= name %> from './<%= name %>.svelte';

export default {
  title: 'API & Demo',
  component: Dropdown
};

export const Default = () => ({
  Component: <%= name %>,
  props: {}
});