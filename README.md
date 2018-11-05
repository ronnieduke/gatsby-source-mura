# gatsby-source-mura
Plugin to get content from a Mura instance using Gatsby

Add this to your gatsby-config
```module.exports = {
  siteMetadata: {
    title: "Gatsby Default Starter",
  },
  plugins: [
    {
      resolve: "gatsby-source-mura",
      options: {
        maxItems: "9999",
        itemsperpage: "9999",
        fields: "body,summary,title,menutitle,contentid,subtype,type,filename,urltitle,display,assocfilename,links,images",
      },
    },
  ],
};```
