<h2 align="center" style="color: red;">MOHAA project to migrate own CMS (programmed in PHP 5) to laravel 9</h2>


My Models: 
<br><pre>
Users:
    atributes:
        id: int
        login: string
        password: string
        email: string (unique)
        email_verified_at: timestamp (nullable)
        info: string
        website: string
        type_id: integer (unsigned)
        timestamps:
   relationships:
        
        
        
        
        
-------from tutorial: -----------------------
Tasks:
  attributes:
    id: int
    title: string
    description: text (nullable)
    status: string
    due_at: datetime (nullable)
    completed_at: datetime
  relationships:
    user: BelongTo
    tags: BelongsToMany


Tag:
  attributes:
    id: int
    name: string
  relationships:
    tasks: BelongsToMany
</pre>
