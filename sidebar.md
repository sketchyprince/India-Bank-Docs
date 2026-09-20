const sidebars = {  
  tutorialSidebar: [  
    'introduction',  
    {  
      type: 'category',  
      label: 'Getting Started',  
      items: [
      'getting-started/installation',
      'getting-started/login',
      'getting-started/configuration',
      ]
    },  
    {  
      type: 'category',  
      label: 'User Guide',  
      items: [
        'user-guide/dashboard',
        'user-guide/accounts',
        'user-guide/transactions',
      ],  
    },  
    {  
      type: 'category',  
      label: 'API',  
      items: [
        'api/overview',
        'api/authentication',
        'api/customers',
      ],  
    },  
    'troubleshooting',  
  ],  
};  

module.exports = sidebars;  
