Download Link: https://assignmentchef.com/product/solved-cop3330-object-oriented-programming-euchre-project-part-4
<br>
<strong>Assignment Scope</strong>

<ol>

 <li>Update classes due to changing requirements</li>

 <li>Adding fields to enumerations</li>

 <li>Add methods to classes to accomplish specific tasks</li>

 <li>Begin developing the front end, or User Interface, portion of the Euchre game. Based on my professional experience working in the industry I have <strong><em>always</em></strong> had to develop a UI for every application, therefore I translate that experience to students so they can have the same opportunity and be prepared professionally.</li>

 <li>Typically, there is a one-to-one correlation of back end functionality to front end UI component. Depending upon the design of the application it doesn’t always correlate perfectly, however with Euchre, it works well.</li>

</ol>




<table>

 <tbody>

  <tr>

   <td width="312"><strong>Back-end functionality</strong></td>

   <td width="312"><strong>Front-end UI component</strong></td>

  </tr>

  <tr>

   <td width="312">AiPlayer.java</td>

   <td width="312">AiPlayerUi.java</td>

  </tr>

  <tr>

   <td width="312">Card.java</td>

   <td width="312">CardUi.java</td>

  </tr>

  <tr>

   <td width="312">Game.java</td>

   <td width="312">GameUi.java</td>

  </tr>

  <tr>

   <td width="312">HumanPlayer.java</td>

   <td width="312">HumanPlayerUi.java</td>

  </tr>

 </tbody>

</table>




<ol start="6">

 <li>The goal is to develop the front-end components of the game Euchre by creating classes:</li>

 <li>java</li>

 <li>java</li>

 <li>java</li>

 <li>Students will also begin to learn writing simple ActionListeners or Event Handlers.</li>

 <li>The UI will be developed in multiple assignments, it is <strong><em>not</em></strong> expected that for Assignment 7 the fully functioning UI is complete.</li>

</ol>




The image that follows is a prototype of what the UI will look like.  It does <strong><em>not</em></strong> have to be an exact match.  The rubric will provide guidance and recommendations on how to accomplish this, however feel free to be creative in developing the look and feel of the UI.




<strong>References</strong>

<ol>

 <li>docx</li>

 <li>Setting up a project in Netbeans.docx</li>

 <li>Netbeans right click menu help.docx</li>

</ol>




<strong>Prototype</strong>

<strong> </strong>

<strong> </strong>

<strong>Deliverables</strong>

To complete this assignment you must submit your <strong>compressed Netbeans project </strong>to Webcourses.

<strong> </strong>

Please keep in mind that the tasks are guidance to accomplish the goals of the assignment.  At times students will be required to do additional research (e.g. Google That S**T (GTS)!) to find implementation options.  In the industry, software engineers are <strong><u>expected</u></strong> to be very self-sufficient to find the best solution for the task at hand.




<strong><em>I have provided multiple code examples on Webcourses that shows how to implement numerous of the tasks below, please reference those code examples prior to asking me for help!    </em></strong>

<strong> </strong>

<strong>Tasks</strong>

<table width="686">

 <tbody>

  <tr>

   <td colspan="5" width="686"><strong>Activity</strong></td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Euchre project</strong></td>

   <td colspan="2" width="486"> </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Euchre class</strong></td>

   <td colspan="2" width="486">1.      Add to method main()Instantiate an instance of class GameUi, passing the reference object of class Game as an argument</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>constants</strong></td>

   <td colspan="2" width="486"> </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Constants class</strong></td>

   <td colspan="2" width="486"> </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong> </strong></td>

   <td colspan="2" width="486">1.      Update enum Face to include the followinga.       Nine has the value of 9b.      Ten has the value of 10c.       Jack has the value of 11d.      Queen has the value of 12e.       King has the value of 13f.        Ace has the value of 14g.      Add field <strong>value</strong> of data type inth.      Add a public getter to return the field <strong>value</strong>i.        Add a private constructor for enum Face with one parameter of type int; set the field <strong>value</strong> to the parameter passed in2.      Update enum Suit to include the followinga.       Clubs has the rank of 0b.      Diamonds has the rank of 1c.       Hearts has the rank of 2d.      Euchre has the rank of 3e.       Add field <strong>rank</strong> of data type intf.        Add a public getter to return the field <strong>rank</strong>g.      Add a private constructor for enum Suit with one parameter of type int; set the field <strong>rank</strong> to the parameter passed inh.      Example code:public enum Suit{CLUBS (0),DIAMONDS (1),HEARTS (2),SPADES (3); private int rank; public int getRank(){return rank;} private Suit(int rank){this.rank = rank;}} </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>core package</strong></td>

   <td colspan="2" width="486"> </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>AiPlayer class</strong></td>

   <td colspan="2" width="486"> </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Card class</strong></td>

   <td colspan="2" width="486"> </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Deck class</strong></td>

   <td colspan="2" width="486">Update class to do the following:a.       Add member variable of interface List, specifically only allowing for instances of class Card to be added named cardListb.      Generate the getter/setter for the member variable abovec.       Update method shuffleDeck() so that it instantiates the member variable cardList instead of creating a new instance of interface Listd.      Write method displayCardList so that is does the following:a.       Return type voidb.      Empty parameter listc.       Using an enhanced for loop, loop through the ArrayList of cards and output to the console the card value, face, and colore.       Update the customer constructor to do the following:a.       Calls method shufflDeck againb.      Calls method displayCardList</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Game class</strong></td>

   <td colspan="2" width="486">Update the class to do the following:a.       Custom constructor Game()a.       Comment out the call to method outputTeams()b.      Add call to method play()b.      Update method setTable() to do the following:a.       Using an enhanced for loop output the names of each Player in the member variable <strong>table</strong> representing the setup of the players seated at the tablec.       Update method dealHand() where the Iterator instance is instantiated, change method call getDeck() in class Deck to method call getCardList()d.      Update method dealOne() to comment out any System.out.println() statements that show what card each player is being dealt if they existe.       Update method dealTwo() to comment out any System.out.println() statements that show what card each player is being dealt if they existf.        Create method play() to do the following:a.       Return type of voidb.      Empty parameter listc.       Using an enhanced for loop, loop through the players at the table; for each player, call method makeTrump()g.      Update method createTeamsa.       Replace the use of the console prompt and class Scanner to get the human player’s name with static method call on class JOptionPane using method showInputDialog passing as an argument the explicit text to prompt the human to enter their nameb.      Store the data entered in the input dialog in the variable of type Stringh.      Add a getter ONLY for member variable of data type class ArrayList that represents the table of players</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>HumanPlayer class</strong></td>

   <td colspan="2" width="486"> </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>IPlayer interface</strong></td>

   <td colspan="2" width="486"> </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Player class</strong></td>

   <td colspan="2" width="486">Update class to include the following:a.       Add method sortBySuit() to do the following:a.       Instantiate an instance of class ArrayList allowing only for instances of class Card to be elements that represents the sorted handb.      Loop while the size of member variable <strong>hand</strong> is greater than zero (0)i.      Create a local variable of type int representing the current position in the ArrayList of member variable <strong>hand</strong>, initialize it to zero (0)ii.      Instantiate and instance of class Card (reference as firstCard) set equal to the first element in the ArrayList of member variable <strong>hand</strong> (hint: use the .get() method of class ArrayList)iii.      Using a for loop, starting at index 1, loop through the size of member variable ArrayList <strong>hand </strong>to do the following:1.      Instantiate an instance of class Card (reference as nextCard) set equal to the next element in the ArrayList <strong>hand</strong> (i.e. index 1)2.      Write an if statement to sort the cards based on suit and face value ranking with the following logic:a.       If the suit’s rank of the nextCard in the hand is less than the suit’s rank of the firstCard in the handb.      ORi.      The suit of the nextCard is equal to the suit of the firstCardii.      ANDiii.      The face value of the nextCard in the hand is less than the face value of the firstCard in the hand1.      Update local variable position to equal the for loop’s looping variable2.      Set the firstCard equal to the nextCardiv.      Remove from the member variable hand the card at the current position (hint: on member variable <strong>hand</strong> call method remove() passing the argument defined in step i.)v.      Add the instance represented as firstCard to the local ArrayList that represents the sorted hand created in step a.c.       Set member variable <strong>hand</strong> equal to the local ArrayList that represents the sorted hand.</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Team class</strong></td>

   <td colspan="2" width="486">Update method outputHands() to do the following:a.       Call method sortBySuit() for each playerb.      Only call method displayHand() if the player is an <strong>instanceof</strong> class HumanPlayer</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>userinterface package</strong></td>

   <td colspan="2" width="486"> </td>

  </tr>

  <tr>

   <td colspan="2" width="198"><strong>GameUi.java</strong></td>

   <td colspan="2" width="484">1.      Add member variables of typea.       Game game;b.      JFrame frame;c.       JPanel aiOnePanel;d.      JPanel tablePanel;e.       JPanel aiTwoPanel;f.        JPanel hpPanel;g.      JPanel aiThreePanel;h.      JPanel northPanel;i.        JPanel scorePanel;j.        JMenuBar menuBar;k.      JMenu gameMenu;l.        JMenu helpMenu;m.    JMenuItem newGameMenuItem;n.      JMenuItem exitMenuItem;o.      JMenuItem aboutMenuItem;p.       JMenuItem rulesMenuItem;</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td colspan="2" width="198"><strong> </strong></td>

   <td colspan="2" width="484">2.      A custom constructor should be defined that receives a parameter of data type Game classa.       Set member variable of type class Game to the parameter passed inb.      Call method initComponents()</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td colspan="2" width="198"><strong> </strong></td>

   <td colspan="2" width="484">3.      A method initComponents() should initialize all the components for the UI and be called from the constructora.       Set the size of the JFrameb.      Set the default close operation of the JFramec.       Use default layout manager BorderLayoutd.      Set up the JMenuBari.      JMenu Game should be added to the JMenuBarii.      JMenuItems New Game and Exit should be added to the JMenu Gameiii.      JMenu Help should be added to the JMenuBariv.      JMenuItems About and Game Rules should be added to the JMenu Helpe.       JMenuBar should be set on the JFramef.        Instantiate member variable aiOnePanel by calling the constructor for class AiPlayerUi, passing as argumentsi.      the instance of class Player stored in class Game, member variable table, at the second position of the ArrayListii.      An integer representing the position of the Player object in the ArrayListiii.      Example: aiOnePanel = new AiPlayerUi(game.getTable().get(Constants.POSITION_2), Constants.POSITION_2);g.      Instantiate member variable aiTwoPanel by calling the constructor for class AiPlayerUi, passing as argumentsi.      the instance of class Player stored in class Game, member variable table, at the second position of the ArrayListii.      An integer representing the position of the Player object in the ArrayListh.      Instantiate member variable aiThreePanel by calling the constructor for class AiPlayerUi, passing as argumentsi.      the instance of class Player stored in class Game, member variable table, at the second position of the ArrayListii.      An integer representing the position of the Player object in the ArrayListi.        Instantiate member variable humanPanel by calling the constructor for class HumanPlayerUi, passing as an argumenti.      the instance of class Player stored in class Game, member variable table, at the second position of the ArrayListj.        Instantiate member variable northPanel and set the size of the JPanel using the default layout manager FlowLayoutk.      Instantiate member variable scorePanel and do the followingi.      Set the size of the JPanelii.      Add a border to the JPanell.        Resize aiPanelTwo so it will fit in the northPanel with scorePanelm.    Add to northPaneli.      scorePanelii.      aiTwoPaneln.      Instantiate member variable tablePanel and do the followingi.      Set the size of the JPanelii.      Add a border to the JPanelo.      Add the JPanels to the JFrame in their appropriate locations based on using layout manager BorderLayoutp.      Set the visibility of the JFrame (hint: this should ALWAYS be the last step on a UI)</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td colspan="2" width="198"><strong> </strong></td>

   <td colspan="2" width="484">4.      Write an inner class to create an ActionListener that is registered to the JMenuItem with the text Exit; it shoulda.       Display a JOptionPane message confirming the user wants to exit using method showConfirmDialog()b.      If yes, exit the application by calling method System.exit() passing the value of 0 as an argumentc.       If no, do not exit the application</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td colspan="2" width="198"><strong> </strong></td>

   <td colspan="2" width="484">5.      Write an inner class to create an ActionListener that is registered to the JMenuItem with the text About using method showMessageDialog(); it shoulda.       Display a JOptionPane message informing the user:a.       Application name and versionb.      Authorc.       Date of development</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td colspan="2" width="198"><strong> </strong></td>

   <td colspan="2" width="484">6.      Write an inner class to create an ActionListener that is registered to the JMenuItem with the text Game Rules</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td width="180"><strong>AiPlayerUi.java</strong></td>

   <td colspan="3" width="502">1.      Create class AiPlayerUi so it uses class JPanel as the superclass2.      Add member variables of type:a.       AiPlayer ai;b.      int position;c.       ArrayList&lt;JLabel&gt; cards;</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td colspan="3" width="502">3.      A custom constructor should be defined that receives a two parameters; one is data type class Player, the other is data type inta.       Set member variable of type class AiPlayer to the parameter passed in of class Player using an explicit type castb.      Set member variable position to the parameter of data type intc.       Call method initComponents()</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td colspan="3" width="502">4.      Write method initComponents() to initialize all the components for the UI and be called from the constructora.       Set the size of the JPanel using two methods to ensure the UI isn’t too smalli.      setMinimumSize()ii.      setPreferredSize()b.      Instantiate the member variable of data type ArrayList containing elements of class JLabelc.       Using an if statement check if the position is 1 or 3i.      If true, set the layout manager to use BoxLayout so it is aligned on the Y axisii.      Else, set the layout manager to use BoxLayout so it is aligned on the X axisd.      Call method displayCards()</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td colspan="3" width="502">5.      Write method displayCards to do the followinga.       Loop through the member variable of data type ArrayList containing elements of class JLabel so there are 5 JLabelsi.      Instantiate an instance of class JLabelii.      Set the size of the JLabeliii.      Add a border to the JLabeliv.      Set the text of the JLabel to explicit text “Card” concatenated with the looping variablev.      Add the JLabel to the ArrayListvi.      Add the JLabel to the JPanel</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td width="180"><strong>HumanPlayerUi.java</strong></td>

   <td colspan="3" width="502">1.      Create class HumanPlayerUi so it uses class JPanel as the superclass2.      Add member variables of type:a.       HumanPlayer human;b.      ArrayList&lt;JButton&gt; cards;</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td colspan="3" width="502">3.      A custom constructor should be defined that receives a one parameter,  data type class Playera.       Set member variable of type class HumanPlayer to the parameter passed in of class Player using an explicit type castb.      Call method initComponents()</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td colspan="3" width="502">4.      Write method initComponents() to initialize all the components for the UI and be called from the constructora.       Set the size of the JPanel using two methods to ensure the UI isn’t too smallb.      setMinimumSize()c.       setPreferredSize()d.      Instantiate the member variable of data type ArrayList containing elements of class JButtone.       Se the layout manager to use BoxLayout so it is aligned on the X axisf.        Call method displayCards()</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td colspan="3" width="502">5.      Write method displayCards to do the followinga.       Loop through the member variable of data type ArrayList containing elements of class JButton so there are 5 JButtonsi.            Instantiate an instance of class JButtonii.            Set the size of the JButtoniii.            Add a border to the JButtoniv.            Set the text of the JButton to explicit text “Card” concatenated with the looping variablev.            Add the JButton to the ArrayListvi.            Add the JButton to the JPanel</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td colspan="3" width="502"> </td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td width="180"><strong>CardUi.java</strong></td>

   <td colspan="3" width="502">Create the class</td>

   <td width="4"> </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Euchre application</strong></td>

   <td colspan="2" width="486"> </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong> </strong></td>

   <td colspan="2" width="486"> </td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Test Case 1</strong></td>

   <td colspan="2" width="486">Test Case 1 passes</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Test Case 2</strong></td>

   <td colspan="2" width="486">Test Case 2 passes</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Test Case 3</strong></td>

   <td colspan="2" width="486">Test Case 3 passes</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Test Case 4</strong></td>

   <td colspan="2" width="486">Test Case 4 passes</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Test Case 5</strong></td>

   <td colspan="2" width="486">Test Case 5 passes</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Test Case 6</strong></td>

   <td colspan="2" width="486">Test Case 6 passes</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Test Case 7</strong></td>

   <td colspan="2" width="486">Test Case 7 passes</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Test Case 8</strong></td>

   <td colspan="2" width="486">Test Case 8 passes</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Test Case 9</strong></td>

   <td colspan="2" width="486">Test Case 9 passes</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Test Case 10</strong></td>

   <td colspan="2" width="486">Test Case 10 passes</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong>Test Case 11</strong></td>

   <td colspan="2" width="486">Test Case 11 passes</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong> </strong></td>

   <td colspan="2" width="486">Source compiles with no errors</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong> </strong></td>

   <td colspan="2" width="486">Source runs with no errors</td>

  </tr>

  <tr>

   <td colspan="3" width="200"><strong> </strong></td>

   <td colspan="2" width="486">Source includes comments</td>

  </tr>

  <tr>

   <td width="165"></td>

   <td width="5"></td>

   <td width="1"></td>

   <td width="511"></td>

   <td width="3"></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Perform the following test cases</strong>

<table width="638">

 <tbody>

  <tr>

   <td colspan="3" width="638"><strong>Test Cases</strong></td>

  </tr>

  <tr>

   <td width="166"><strong> </strong></td>

   <td width="166"><strong>Action</strong></td>

   <td width="307"><strong>Expected outcome</strong></td>

  </tr>

  <tr>

   <td width="166"><strong>Test Case 1</strong></td>

   <td width="166"><strong>Project view</strong></td>

   <td width="307">Completed project view should look like figure 1</td>

  </tr>

  <tr>

   <td width="166"><strong>Test Case 2</strong></td>

   <td width="166"><strong>Regression testing; Run application </strong></td>

   <td width="307">The JOptionPane.showMessageDialog() method call should look like figure 2</td>

  </tr>

  <tr>

   <td width="166"><strong>Test Case 3</strong></td>

   <td width="166"><strong>Run application;</strong><strong>Updated method setTable()</strong></td>

   <td width="307">Output should be similar to figure 3</td>

  </tr>

  <tr>

   <td width="166"><strong>Test Case 4</strong></td>

   <td width="166"><strong>Run application;</strong><strong>Updated method .displayHands()</strong></td>

   <td width="307">Output should be similar to figure 4 where only the human player’s hand is displayed</td>

  </tr>

  <tr>

   <td width="166"><strong>Test Case 6</strong></td>

   <td width="166"><strong>JOptionPane Prompts User Name</strong></td>

   <td width="307">JOptionPane is similar to figure 5</td>

  </tr>

  <tr>

   <td width="166"><strong>Test Case 7</strong></td>

   <td width="166"><strong>Euchre Initial UI displays</strong></td>

   <td width="307">Game UI looks similar figure 6</td>

  </tr>

  <tr>

   <td width="166"><strong>Test Case 8</strong></td>

   <td width="166"><strong>Euchre Game Menu</strong></td>

   <td width="307">Game menu looks similar to figure 7</td>

  </tr>

  <tr>

   <td width="166"><strong>Test Case 9</strong></td>

   <td width="166"><strong>Euchre Help Menu</strong></td>

   <td width="307">Help menu looks similar to figure 8</td>

  </tr>

  <tr>

   <td width="166"><strong>Test Case 10</strong></td>

   <td width="166"><strong>About Menu Item Action Listener</strong></td>

   <td width="307">JOptionPane displays similar to figure 9</td>

  </tr>

  <tr>

   <td width="166"><strong>Test Case 11</strong></td>

   <td width="166"><strong>Exit Menu Item Action Listener</strong></td>

   <td width="307">JOptionPane displays similar to figure 10if user selects yes, the application should exit;if user selects no, the application continues to run</td>

  </tr>

 </tbody>

</table>

<strong> </strong>




Figure 1 Project View




Figure 2 Display from JOptionPane.showMessageDialog() method




Figure 3 Prompt for User’s Name




Figure 4 Players at the table

Figure 5 Only human player sorted hand should display




Figure 6 Euchre Initial UI




Figure 7 Game Menu




Figure 8 Help Menu




Figure 9 About Menu Item




Figure 10 Exit





