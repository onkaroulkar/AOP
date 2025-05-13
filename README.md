# AOP Concepts in Nutshell
1. Joint Point(when): Think of it as a scene in the movie of your program's execution. It's where the action heappens!
2. Advice(what): This is the action. It's what happens at a perticular scene(join point). It's like a plot twist in your program execution.
3. Aspect(Where-conceptual): It's the script of your movie. It defines what plot twists(Advice) happen and where (pointcut).
4. Pointcut(Where-Operationl): It's the specific scenes(Join points) where the plot twists(Advice) occure. Its like a bookmark in your script(Aspect).
5. Target Object(Whome): This is the main character. It is the object that experiences the plot twists(Advice).
6. Weaving(How): This is the director's job. It's how the script (Aspect) is turned into a movie. In spring this happens at runtime.
7. Proxy(The Double): This is the stunt double in your movie. In spring AOP, It's the object that is created after applying advice to the target object. It is the one that takes the hits, performs teh stunts, and makes the main character(Target Object) look good.
8. Type of advice(The Genere): This is the genere of your movie.In spring therer are three types of advice: Before,After or Around.
    # Before(The Setup): In spring 'Before' advice is executed before the method execution.
    # After(The aftermath): In spring 'After' advice is executed after the meathod execution regardless of its outcomes.
    # After Throwing(The Plot Twist): In spring 'After Throwing advice' is executed when method exits by throwing an exception.
    # Around(The full story): In spring AOP 'Around Advice' is executed both before and after the mehod execution.
   
